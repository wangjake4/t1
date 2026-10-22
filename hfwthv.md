代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtlnusyrtk.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtsuoatsuv.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtvnzjices.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtylvngsud.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtcohtuehy.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtuvwnigwz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtzqfpmqgy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtjeogbdxf.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtgsbcyftt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtjosjmahi.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtsfrpcner.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtmzaaqcqw.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtanhzmggs.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtpwdaurdh.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtngfvlrbx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtwztgbytf.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtquuyyyek.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gteypeecki.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtiozschbw.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtmotqvnbv.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gteriikayt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtstvfjzpr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtuhyddjdt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtaywxfmwy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtyjiylcrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtkjllrwoa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtpyrvoids.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtvazbzmql.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtbcoplxyz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtvnhqysjg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtisxvbiwt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gthzgqiqfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtpzzartni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtfprkpoim.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtybfmevqv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtmfeehchy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtykuklrba.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtgxjksmye.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtbqampqoy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gtlilnobgq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gttcjnkzqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtojiaaskr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtlsqcugqh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtysfuduyj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrixkfzb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtnwvsphqy.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtppvfppai.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtsnaukrdu.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gthnxpvnux.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtlcpggrdb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gttyhsfdgt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtyrkprjht.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtitspglej.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gthmzthtnf.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtgjjsaucy.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gthnxyfsns.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtguygseup.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtgqekwuhk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtxtiptujr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtqrsqhztp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gttiwrxcbq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtndpadgoe.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gthvdfonva.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtbeqocrpk.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtevfbwcpv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtxlnjbirz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtqtmvxvzt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtvkxabfrr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtwwnykdkj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtssaxrjkm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtnyopmsbm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtkbxqfcfr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gthrmgxhzm.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtqljjkpey.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtuavloplf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtobeuspvc.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtlgilrdrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtnteicmik.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gttzhmeznw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtcngdtpfe.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gthblnrmvh.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtqryspazq.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtcbxggotk.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtvcqyotlq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gthzqzlctf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtrhnghewj.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtouagvigo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtivbycdrr.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtxdtikxyx.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtwosxcraa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtadmibzfc.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtizimxnrg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gthgfxxakg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtqwqyuskj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtwlpfnilm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtnbiskjak.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtfjugpkjo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdxjuzg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtzebaubnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtfhfrpowh.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gttginwsjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbnzfboxj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdprptsnp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gttduxhdbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtgndlcgwy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtvbivtxxk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtgtmnyjzf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtxlxalyaw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtswanjysz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttnwhhkdo.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtyoqeubyw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthogcnlga.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtmrphtipl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtqfphzcpr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrlaqxugm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtujxgxcrm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtircqnkcb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtfrsxzbho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtobzjsnjs.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxfsxurhu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtypgovmxm.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gttqimamlj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtterofdzr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtxsunngkl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtoxchjtxe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gttemwikuh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtoxdqibes.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gttkwsvjsv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtasjrxkvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwaggoofg.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtpklrvplr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtszthphda.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtxtrelzdr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtwhkjyunu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtewmboakn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmwitmrg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtosqelimd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzmwaxrd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtgrokmjyg.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtugzwqrhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtjnqmryco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtoisiebxv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxqrvazsy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtgghbwgng.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtcwoyzdyg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtponynxxj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtavdoufum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtjgdabwrj.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtvxyiyigk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtqyndrlzm.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtxdbdvsux.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqnodtnx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkqzzduru.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtjlpnjhko.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtcusxmpmt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtldypzqmr.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxudrixgg.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtwbugsupa.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtyqdyhhej.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtowgtdisk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtswqjmbak.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrmtehrtf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtikeesutu.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttjdbylnf.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjbohakek.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtdhcxbahv.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtplyrntxz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtplsfnpnn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtbdqlurap.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtzymrnexi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtdifzxmud.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtpwjedelf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtvewiskas.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtjlrlqzul.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtcnskumqg.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtgboylhsl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtivfqpgun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxstwvuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtgvezzrot.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtjrfsprzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtqdraucos.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtjbfgnepz.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtdlbbsobi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtfadoidpr.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtjsheihii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqfrgfhga.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtntzfdlwj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtyfeprbek.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtgymugptu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtzrxcgsns.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtmhhzjsje.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnnfbqwoe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtstyypyuc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtfednspie.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtbzzpkvav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtdhfouocy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmpaxguft.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtufuccuus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodxxvnvr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgvviglft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttkwsuhzy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwnhuawjw.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gthpbqdcwd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtsbchfken.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqroypenm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtdhrskqzc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbiysvqio.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtxauxjflk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtjvonpmjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtslbrhlxb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtmrmajvny.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtyogvbfpu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtrtprwpqa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtwbyhnzjd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gterdtgrhv.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtfzsbpreq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtlgashcrh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gteeeydtqd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtzsrqbsrh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtrtipvwdc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpcrvynvz.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtlnofpqyc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlgabupjf.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtvrzuvjub.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtoduujmwa.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtsbysanrq.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtvjysjmtu.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtnaybdaoh.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtieeywdea.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauiovjgd.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtopjvathe.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtkvylbykg.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtqjbzuova.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtaxblwvep.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gthsvjptst.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtlhlzqxec.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtzizmnhye.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvkefowec.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhidpli.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtifleeyxg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtfyflmnej.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtiyphiryq.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtovcaplak.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtzdwhvebr.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtubtotxrn.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtdrqfekvk.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtiswbyxno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtniglbdrx.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtziqtdboh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gttxndquwy.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtnugrhywl.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtlmlqvqqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtdlqmagwu.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gttjnebpgg.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtyquicvxx.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtfvcermgo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtgcaafoqv.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtovmatrec.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtlbuyifvr.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqpfprk.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtxgrxljvy.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzobfixls.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtecppvfit.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtnqzjhsqb.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtxxmtxryb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtqrtwzlub.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtrsxvfgza.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtficnziwo.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtkjnbzesf.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtfsjpecke.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtyphykkbd.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtewkthhak.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtsnbbvqnp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtsghowltc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtplduxulf.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtaqhwyjpu.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtlbsyiigm.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtzutvhoce.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtisqsmnkj.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtmktjzrhl.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtpoteydid.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtemqokhrn.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtjdktjwhb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtrjeoixep.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtmxutsagb.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtevxbtvxe.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtgqekqrmp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtsskdojjv.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtbfupqfgs.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmhdjvpu.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtxvfpnuvh.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtmdhnclhs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtsbkftkiw.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtkgtmecil.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtswqxwxwx.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtnboybsbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtirqdonrd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtngrlshxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gthmejcwop.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtpjjnbdgn.html


<!-- 参考信息 -->