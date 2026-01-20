# Ansible Mock Exams

A collection of hands-on Ansible mock exams and practice scenarios designed to simulate real exam conditions, reinforce core concepts, and prepare for certification and real-world automation tasks.

## Repository Structure

```
AnsibleMockExams/
├── LICENSE
├── README.md
└── Mock Exam X/
    ├── Challenges.md
    └── solution files/
        ├── challenge1-solution.yml
        ├── challenge2-solution.yml
        ├── challenge3-solution.yml
        └── challenge4-solution.yml
```

## How to Use This Repository

### Prerequisites

- Ansible installed on your local machine
- Access to remote servers or a local Ansible environment (e.g., using Vagrant, Docker, or cloud instances)
- Basic knowledge of Ansible concepts (playbooks, modules, inventory)

### Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PSamardzhiev/AnsibleMockExams.git
   cd AnsibleMockExams
   ```

2. **Navigate to a mock exam folder:**
   ```bash
   cd "Mock Exam 1"
   ```

3. **Read the challenges:**
   Open `Challenges.md` to view the practice scenarios. Each challenge includes:
   - A problem description
   - Specific goals to achieve
   - Hints about which Ansible modules to explore

### Approach to Challenges

1. **Attempt the challenge first:** Try to solve each challenge on your own before looking at the solutions. This is the best way to learn and prepare for exams.

2. **Understand the requirements:** Read the challenge description carefully. Note the specific modules mentioned in the "Goal" section.

3. **Write your playbook:** Create an Ansible playbook to solve the problem. Test it in a safe environment.

4. **Check your solution:** After attempting, compare with the provided solution files.

### Solution Files

Each mock exam folder contains a `solution files/` directory with example solutions:

- `challenge1-solution.yml`
- `challenge2-solution.yml`
- etc.

**Important:** Only refer to these after attempting the challenge yourself. The solutions are provided for learning and verification purposes.

### Running Playbooks

To run a playbook (replace with your actual inventory and playbook):

```bash
ansible-playbook -i your_inventory.ini your_playbook.yml
```

For challenges involving Ansible Vault:

```bash
ansible-playbook --vault-password-file get_vault_pass.txt your_playbook.yml
```

### Tips for Success

- Focus on the Ansible modules specified in each challenge's goal
- Pay attention to module parameters and their effects
- Test playbooks in a non-production environment first
- Use Ansible documentation for module reference: https://docs.ansible.com/

### Contributing

Feel free to contribute additional mock exams, challenges, or improvements to existing solutions. Please follow these guidelines:

1. Create a new folder for each mock exam (e.g., "Mock Exam 2")
2. Include a `Challenges.md` file with clear problem descriptions
3. Provide solution files in a `solution files/` subdirectory
4. Ensure solutions are well-commented and follow Ansible best practices

## License

This project is licensed under the terms specified in the LICENSE file.

## Disclaimer

These mock exams are for educational purposes only. Always test playbooks in safe environments before applying to production systems.
