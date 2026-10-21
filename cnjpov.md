代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtvungbcxr.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtjgzsvraz.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtbihgsztd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtmdwcmnda.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtuthrcxaf.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gthffhfnpb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtbbrkcyff.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtrkrebrak.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtlhqlnhwt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtwtrphrni.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtqnffovjg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtoubstoqn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtiakykkfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtahmbtogn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gttpixzegy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtwzctbpvu.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtqvitznaf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtiztfsjke.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtajrlkngg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtpualqflv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtrreyedzx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtygejjhej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gthuysckjh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtfooclgbs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkozbveh.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtuiouhlsv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtmnnbookh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtfnrcuboa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtmjrpdobg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtvvwanrdo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtclypftpg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtoyizzqbn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtlbmkjfek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtemgdmyao.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtyhxxzrla.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtzzhcqkqi.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtdgidiflf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtwawdhaad.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtmdokjzac.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gttjpfwxmh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtiskjalhb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtlqeqgedz.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gttnqjdaqg.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtztdpwuzk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtrunfwfya.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvxrnzr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrxzbzyc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtuvxjqhei.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtxlifcqqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtiiyxrjgf.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtebxhexgk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtuqyavihs.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtiyswjwvu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtsguvvpnq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtoiwozkyo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtpcsbufet.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtxeeubzgp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtdcrtuzpm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqmjtnjr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtlkeevnkf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtiymawu.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtpjodwfux.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtcgxsgpiz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gthnfbflin.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtwxstkifi.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtqxclnuea.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtnqaenjqm.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtpiukjmqk.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtfkdhtiql.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtiujjjiiq.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtcherbbjr.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gttjyjzfex.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtlxpafuvo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtyuvbrhsx.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtcsobssvv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrrmiawwc.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtokgnvpfr.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtmcbqjqdt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtrvwtoyzq.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtwoktygzh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnlylpet.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtmkaaccng.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtkgququbl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtyttbfeer.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtgqmyearr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtlrxulyig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtjqcndbgh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtyelazdox.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtlrxtczrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtsbiwlmia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtilndivdn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtodnwypza.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtwxclwqtk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtenxjdedd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtdtlhrubx.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtjabynfil.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipqnrblb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmkpemfjs.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtptpcwtrx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtayzkqudi.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtdwmaqror.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtkjstficf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkikiphpz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvivunvmd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtvizoceng.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtgupyvkgv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtutstqfax.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrcglfzgr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvrhzywcf.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtyodyjtom.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftrvverc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmmczfpux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxptovrve.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtzhcpunsb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtxlkstyji.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gteokwsgca.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtlwisobkm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtrkhcqysv.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtvfdrkftl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gttvluzxsk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtlawhdgjr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtneucnumf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtzvxzskno.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtspjlsvup.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtigbruqfb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtltmmfnck.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchqgndlq.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtmbqoyrsw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjlxpjgd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtwyslzapj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtsncedyuc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtjyjyffdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtobosmiah.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gthdlkiqjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtohakiwvh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtlpjtdmis.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtpzcrntqi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtuuptcdub.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwfavhatv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzwhhuwpm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttoutpkcp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnlgqqlfh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtcgikgdkr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbwfbenws.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrtehqyjd.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtaehfactt.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgxdjmnbd.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtudkcoxhy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbllddyhd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpkcfabkw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtjpivifpt.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtilhdqqkn.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabguzgbt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzswylpqp.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtynhevrfa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gteflcnruy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtmsdbaacx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtbqxeyqyc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtqzejttmo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtqknufsvv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gttjywcmvp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtktvphnhr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtihdpfyln.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtwbilfrsl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtjjyvuihz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtvzzqkyxj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtxjokwnhj.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtovdgndep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtxznhgimr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtuhapocao.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtlnlagmhq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtukyunfbe.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtaykzhdfs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmijtmrcy.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtyfpmoany.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtdrbygpmr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtxcaycben.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtfbewpcjz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtlsndiahy.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthtspvtns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtwkbctkzf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtoxrvxalz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfkmxkefc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtdyeqltga.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtphctzsah.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpeaiacgl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtpwdslbkn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqdrynnrn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwukpjwan.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtbjpxdarj.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdsrzhdiq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsornqnua.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtidgvpfnx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtygbnqovm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrsgyoovo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtpjhnxgiq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtvfstctcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtuvzhpjtw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtpksulslj.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gttlzqbqty.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtytodaehz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtrseopspp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtmlhoqrvo.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtbavqpfbs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtwrnqdrgf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtmlmbaseh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtayskuuef.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslrunozo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzozsbcou.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtysjmoian.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtibfcnhom.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtrjyeltzj.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtvqrovogv.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtcntizoty.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtyxafqqud.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gthkhhmxrh.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbrpsvptc.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtpbvkcuos.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtceyxurgx.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaqgnoen.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtjckkdint.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtnrsonagc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtttejblzw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfspkjlhn.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtympvmgpz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsxlcmnsq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gttsaiguqi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtysjfhsgy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtgtrviarf.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtpgobnrhi.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtprigbdex.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtaoklmamx.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtqcuczt.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtphvacmau.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtzpvjhuav.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtimswdesi.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtcoyodpya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtvnlgpzap.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtpgbebgso.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtukegjcpa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtdppjdjvo.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtyoqggtqx.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtisvyfxul.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtnrepmcqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtwdetobzv.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtaevhoicc.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtbzzgqohy.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtagdtvazi.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttwsspui.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gttxmxlepu.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtltbskzwe.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjzlpcon.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtofdemetx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtfyopoapb.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtpgzhgqps.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtmxnjbosv.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtpopzdwft.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtmzyeaaxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtbmuvaays.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrpchmgin.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjicdkuam.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhbofdpg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtkgpiseuc.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtlgjsqrfb.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtxzinbvvf.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtrnpzkatr.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtlmxfxyaj.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtehfecrzg.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtbzyxzdpe.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtmdgowttf.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdabnrim.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtgckcmihr.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtqibfcdaj.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtgrxorpms.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtxtubvmly.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtugzeohom.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gtjrvepayy.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gthktnzyju.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtqvtuuszr.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtpukqkvtv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtbcxmyvna.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtttiqvrep.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtlcetsvuu.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtrbynnhnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtfikuoegy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtvrlstqyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtlcgeczom.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtizasprhi.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtorsbfljr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtxrqyezya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtlrlubvid.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtoiogevek.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtaujjzawc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gthhviqlaz.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtxsnlgftl.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtlqtnihxc.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtyuhektnd.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtrrmuinyj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtfpkwywxa.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmpzpefk.html


<!-- 参考信息 -->