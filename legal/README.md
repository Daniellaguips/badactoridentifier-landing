# Legal Package - Bad Actor Identifier Platform

This directory contains the complete legal documentation package for the Bad Actor Identifier Platform MVP.

## 📁 Document Structure

### Core Documents

1. **`tos_leader_v2.md`** - Terms of Service for Community Leaders
   - Comprehensive terms for users with Leader or Admin roles
   - Covers data collection, reporting, community management
   - Includes privacy requirements and compliance obligations

2. **`privacy_leader_addendum_v2.md`** - Privacy Policy Addendum for Community Leaders
   - Detailed privacy requirements for Community Leaders
   - Data protection responsibilities and member rights
   - Incident response and compliance procedures

3. **`member_notice_v1.md`** - Member Notice
   - Simple, clear notice for community members
   - Explains data use and member rights
   - Contact information for questions and requests

4. **`member_tos_v1.md`** - Terms of Service for Members
   - Comprehensive terms for all Members
   - Mr. Number/TrueCaller-style legal shields
   - Profile visibility and report consent framework

5. **`member_privacy_v1.md`** - Privacy Policy for Members
   - Detailed privacy policy for Members
   - Data collection, use, and sharing practices
   - Member rights and data retention policies

### Supporting Documents

6. **`tos_v1.md`** - General Terms of Service
   - Basic terms for all users
   - References the specialized documents above
   - Used for general user acceptance

## 🔗 Cross-References

### Document Relationships
- **TOS Leader v2** → References Privacy Policy and Privacy Addendum
- **Privacy Addendum v2** → Requires Leaders to provide Member Notice
- **Member Notice** → Points to both community leader and platform support contacts
- **General TOS** §9 → References all specialized documents

### Implementation Notes
- All documents use consistent versioning (v1.0)
- Placeholder fields marked with `[Insert Date]` and `[Insert Contact Info]`
- Cross-references use relative file paths for easy navigation
- Documents designed for easy customization and deployment

## 📋 Customization Checklist

Before deployment, update the following placeholders:

### Contact Information
- `[App Operator Legal Entity]` - Your legal entity name
- `[Platform Name]` - Your platform name
- `[Insert Date]` - Effective dates for all documents
- `[Legal Contact Email]` - Legal department contact
- `[Support Email]` - Technical support contact
- `[Privacy Officer Email]` - Privacy officer contact
- `[insert community leader contact email]` - Community-specific contacts

### Legal Details
- `[Jurisdiction]` - Governing law jurisdiction
- `[Legal Contact Email]` - Legal support contact
- `[Support Email]` - Technical support contact
- `[Privacy Officer Email]` - Privacy officer contact

### Platform-Specific
- `[Platform Name]` - Your platform name throughout
- `[Support Documentation URL]` - Link to support docs
- `[Legal Support Address]` - Legal department address

## 🚀 Deployment

1. **Customize** all placeholder fields
2. **Review** with legal counsel
3. **Deploy** to your web server
4. **Update** `TOSVersion.text_url` in database to point to hosted URLs
5. **Test** all cross-references and links

## 📞 Support

For questions about this legal package:
- **Technical**: See platform support documentation
- **Legal**: Consult with your legal counsel
- **Privacy**: Contact your privacy officer

---

*Last Updated: [Insert Date]*
*Version: 1.0*
