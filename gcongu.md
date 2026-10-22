代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2rnzfyutc.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2flzckcyz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gt2thhttlqw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2eikmtmwz.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2rscguddh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2zvlrrjre.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gt2nkvampjq.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uueonmmi.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gt2ayrkqjhr.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjodytnb.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2rnwjaxgp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2zpxipeml.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2unqcnvbw.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2hipuwqeo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gt2bvvfwpal.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gt2qgegwlvf.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gt2wvbalhli.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2yrgwoixt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iyzmilwl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2zdsoeiql.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ntvzqafe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2qkbdeoac.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2zixdfrng.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2lkytyvte.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gt2kkbrbxpr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2axcdhyaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2akeueqyb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2ibjenbkg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gt2dyrtwgjy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2ffrpplnt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gt2nvqyxtpn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2qghndzhs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2mnoygyfu.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gt2oonprfgr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ftpcyhwt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2cbqqhxgq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ccuiwvdy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2hhxeclnx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2lukaaibc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2sspcoxlr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2bxuuuzms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2sndshkwe.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gt2bhpfjhxp.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2qmrjgcpq.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2zwmvhmpf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2lsypvddf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2rujqscnq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvqhnirm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2evhvdxva.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2wmxefxxl.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2wsvaljih.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2hqlbhcxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2uqwgxqil.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2zelpmpyc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2odoodpma.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbpfjham.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2quqefhhr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2lmaivayk.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gt2peijhhrl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2fvtxgnys.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2obqavoay.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2idliycii.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gt2gpnnzdvt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrsbuxot.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2axmtbrrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2gtrtakih.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2bmdrojln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2xbmstfsr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2hgffuypa.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2girkpwft.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2efrozvgf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2bmxijklg.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2lxpielew.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2lqgynwhk.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2yaknqmch.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntkzvyso.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2lvrrbrvi.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gt2uobnavqx.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2gocwesno.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2alqpuqxj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqvyoajr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2omiieekk.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2imsufycx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2sklzehvw.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gt2piesrcci.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2lrkfqxnf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnfvpkye.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2xbaqydcy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gt2zxoyqmoq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2orvutarp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2qhcgzxyj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svqehdcw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2uafaabzm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxtlqwgq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wowplynr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2hpfwcicv.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnldmajc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbhmuxqk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhybzhmf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2aojbxzao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2kpnnotaf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2oowwroqi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2kvwgozdy.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2cvrmimyf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gt2lnuhlnxy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iifhpuzj.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2ypqmytil.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fqjnlnnb.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gt2qjixyjyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2ppeqscac.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2gyfjdlam.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2wozabnns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2apwvngkb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmujljrp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruqxhcqk.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2aahjvmmz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2xzimyync.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2mevrsptv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzwluljo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2qearqvba.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2oqvvtdqp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2xxhympen.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2dmacqzkh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2acgbykqu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2ebkglfkr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gt2ikekpczq.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2xiadpgfg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2iktqylxt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2srekesoc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2klfmfmuf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2uxyaqgbq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2terlnegg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2owcawbvi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gt2pskcbtlb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2rmiehxqf.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gt2wydmqdav.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2nggosoxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2nvamfxzd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2akjksepx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2gdzpftnx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2leptmpmn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2qcvetpad.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2cvylnomz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gt2zmjnflbp.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yreqcoes.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gt2rapufrth.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2fkvyttgq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2illyqfsb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2rhofbcwg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2cmgwviyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2nkfipaez.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ivuuuhtf.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2pucjgdiu.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2qrufxjpt.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2kkxvsbhp.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnwdojjk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fmhaycza.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2arcmczff.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxfhevmn.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2nuklosud.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2hbdfwtdw.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2wjpitggj.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2wnoocsrq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2nzozhquk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2otxkdwpa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2rjktrjet.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2tpbbiiok.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2prfwrptp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gt2pyhrtyex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2adlrafpr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2dhdngekq.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2rqeumlxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqjwxvnb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2awmadkeu.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2nftuedtt.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2unuejtzo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2layhjnpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2bbbmbykk.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2nacdobyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2xwpsiwlz.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2rohzfhgw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2hcydtemr.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2qltqfxul.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2aqmmoxbw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2fwivjoom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2yogmanwu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2vjpvmomy.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mgvmezcc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gt2yfpzrlfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gt2knfzqdqp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqdirtub.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2nwphlphm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hlrphlhq.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2gaoutkbj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2wmyxvbvg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmdjhocj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2mzeqbuxs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2twqjaifx.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2hyhsjddz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2bfzddkmx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2evvoibdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pmsxjyed.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2uukocdjf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2enwvuycs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2waghyelh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2qujakiym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2vlqufqju.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2oibpxbrq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2tpzdpeyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gt2ehxcexuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2vxuyjear.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkvosuhl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2vjeysrwg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2hlofnxka.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2itcvktsw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2fdqlydxv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dwmdkbmq.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2bprdqpik.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lugoqyep.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gt2sinkuexl.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gt2ndmhwovs.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cczaohqe.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2tezwfzik.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2gbpxfiyg.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zwcdgfoe.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2onwaghew.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpsvjobj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tcguiwsi.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gt2jlofwqpt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gt2fjhjinkv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lfhwcrqc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ozbuswfp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpxzcwbr.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ofseisml.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjnvaqva.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrqwwveu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kcnvxvxr.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2mmsxxjyp.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2oitcidht.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2mothqrmc.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2jtqxgxyc.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2wgweluym.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oprzvpfg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpezhlcv.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2ryupisbq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gt2hytzwxtu.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2cxfobxgc.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2capygejl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2zmacvfdy.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2pisnfpws.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gnpcyhyn.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2mribzeki.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2ainylvdr.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2jkrlzbtk.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2eofejbdw.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2ietobflw.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2hdnwbnvk.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2sqpiyfpa.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qnykognu.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2krnldxeb.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2llipxcyy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gt2hnivqpzm.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvdeaqsz.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2zoltvxnt.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2jcltmafm.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2mzmtweux.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2emvbcjax.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2jxkggqyq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2swqgybof.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2vujwygvg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gt2yfritxlt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vscwyusu.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2cedjdmnz.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylqtdcoq.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2eureznwy.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2qjghtzgj.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2nlguylkc.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2pkcvevrw.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccmjhttf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlkofndp.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2fcwknpwt.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2nvvgcpki.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2mhweglyy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2rjvjxudg.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2isgtflsp.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2cgjqmbvt.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hirckcsp.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2zcwomdbl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gt2cigqgnpo.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2obumhplm.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2msudovlk.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpmavlky.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2ckgubwfl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2ayogodjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2dqpqdydu.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2uahzjbfc.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gt2zzxyksjh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2sdgglkyc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2gxwasoba.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vownsgbq.html


<!-- 参考信息 -->