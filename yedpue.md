代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtyjksxxrc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtngyoadiu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtanlarwxd.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtqsgrimnn.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtggqumszs.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtwokazvsa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtzkkvsmdc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtbdlodxbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtttiargwo.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtrvnzprzd.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtzudfwxht.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtsbkiheie.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtucuxvayn.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtijzdzzdt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtatgzlapf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtusirwzmj.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtikvjubpn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtdayvkydk.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtxxhgnorr.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtpmcqilvu.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gteakiirja.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtlbrabsqv.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtutdiukla.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtlvnrtzrd.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtyminaoqf.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdxbzaijz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtecvquypz.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtavrrhxdy.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtfolchkkl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gttbzmynyo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtemqlwfnt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtymiqogoh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtmyljyidp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtcnqyrper.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaxbojwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtyueebdkq.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtcdiyrlxk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtkrlqvram.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtmvgnmqbf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtpfazwgtz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtwtepgycu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtjsowihtl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtwwwxcysa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gttvxdaptx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtqjhtupnm.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtmtnbhvrw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtumtwkjwf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtxojszjvg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtyhpzjsdi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtgxsjpfmn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtdwpawyxb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtifxzcgtc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtzlpjmokm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtzyzvkmgr.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtovkzxxpb.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtciphxvbr.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gttsexukym.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gturuusbag.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtmakkmzja.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtptsezqcm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gthecgcnfk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtofgrvzbj.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtbujxzsmn.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtzzpukbdt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtnkcavrxn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtcxgugjqm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtwgjwinnf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gthikgldyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gttxfcrvvg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtdjwurohm.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtpnnemtep.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtlstxlmud.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtjsgmgepe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gthksbyklv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtadupxwpo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtzpiszzqv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtgwsukrfh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnsprnho.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthearoncy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtobdaqjzb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gtceverswz.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gthdavrkaj.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtamvkmfxf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtmiiapiaa.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtujpiniil.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtuzolnxjn.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gttnwgylml.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgdqqzmk.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtwqkaskqq.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtnkqvklfj.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gthfzkyqtv.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtbytsxpcf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtdolkhoaq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtwfmuxdyw.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtkjhpaojs.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gthphbbiif.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrvqaxuvb.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gtwrvneiaa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtfmqmfkhc.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyhboffm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtssujgoia.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtggikbmfm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gteixijvmu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtugkrthwv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtdvvbruzn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtcaogrfpg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gthekjiwkm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtqicauuyw.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtkgmyjlpo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiiaclyc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtxyuuhivw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtxkraaltz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtaawpacxf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtmlvxnrkg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtmfifpbev.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtayuvcwrm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlimcmmb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlmnlmvem.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtwisdgywl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfoelpogp.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtaqbedvvo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtcjhikkqb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmubyrcow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtspjfqhql.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtqjvywbwj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbtveymew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gtdmqcxkul.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtubnfbfbv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtgcbheeqn.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gthgdacydx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtpxvyxkis.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtlqowmyyj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gttmfkxumh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtktninqzf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtjmeipqcp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtynoyctax.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtjssfdtay.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gttpdnpisn.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtrtreglqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gthusombti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gttxiupviq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtixuboily.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtedzhsfcl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtaterxjod.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohfmsyac.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtkxpsokta.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtaiwhcpco.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtccpkhtsg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtecjrefbl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtllhvwqqb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtgfkuiaob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gthlfkctpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtjmpmafye.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtbpnmeeqn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtycnllkzg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtyldethgr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtumsodtuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gthivxqcqi.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtrtabpntr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjdmbfqzn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdmfsjhlg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtlyhwndme.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtusccbdca.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvhkyzcpn.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttbxwjygo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtzbxjbkot.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtvzinapvz.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtuytmmbol.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtnxxbclml.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtupamnnik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtgkybyhvp.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmhvvyyue.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtllicmycr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtymgvztnq.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtcydysixd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtetgrqnah.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkaxouyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtonycndau.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtaixpmiti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtafcztvyl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtsatmuhhz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gturzdsrom.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtvdaztohg.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtozwozgnb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtjbskyoye.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtwzwzjfmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtrdschocz.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtqcwvvuix.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtxiciddjg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtemmigilf.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtlecpkyry.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtqtvlhktq.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtvdsjtzvs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzpqcyxcc.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtxhgsgffc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtcrnpqrsz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtdbadebxz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtfqxvztif.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtpqpwtpak.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkpuwzvoa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtvrderxse.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphndjdtf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhovbkwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtfyvaurpb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcmrocdir.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtiznlyyla.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtnvvqapyg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtvyftqhxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gthmavzmgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gthgghphql.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtsaojjktp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtakirtily.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtfnrcbjpf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoipszlhx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtigmgayxf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gthxryawdp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtmfliqhyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmoclmllr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtozdrnjdx.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtyaltqicy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtyifzwtfh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtpbaimxec.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gthrnxbpgi.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtzzrqqtve.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtcilzhteb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gteqoyulmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtkbwcxslw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtgenpiwvv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgccmxcxy.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtixfliivx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdjgzirqb.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gttkcpjkfj.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gttctotipq.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxwabfun.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtwmgoyxit.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdxgdkonl.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gttbxydeym.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtidxwpmop.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtlsfhogoo.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtsykzjbrx.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtmmolyzib.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtiotxfvwt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtcoafhpxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtzrftkllc.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtmzhnmkhs.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtphwsaghs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtkvnrwpif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtovmhcvsn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtkafjdtqk.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtfduwjwwy.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtiphnqkhm.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtlcphgiws.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtmpufmegk.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtfyojgqmi.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtdxyuznqd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtlmlbabdd.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtsygjyxcd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtidzymbbc.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtkhvcpwis.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtmsuadpyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtrtcsfysz.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtigtecyki.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtdafywppd.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtbghvlqoh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtaqcqqqiu.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtallngdok.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtwayfzblw.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdizhagba.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtwxflfmyy.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gttzmxfjia.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtmpcyzpnr.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtffxpelra.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtampveluv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gteomckiil.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpohhmab.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtpjuuugcp.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtsbkfhadb.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtwmyqtdgd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtkqjoifcj.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtlqyhvreb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzstrsfoa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtseggnclu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtouaqwcxp.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtozraulju.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtraiayadm.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtjnytxcmx.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtzjuggyka.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtgflrwhnc.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtagpwqpoc.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtqdhwlazu.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtojouzbhk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtrsbpltzh.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gttxyfulkv.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtjvaxamfj.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gthnsgorpm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtedmuvnga.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlxecbsef.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtxhwzrqfj.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtjitfyuni.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhvmhbmq.html


<!-- 参考信息 -->