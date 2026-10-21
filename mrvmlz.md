代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtywpsmfcm.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtfsfksmyu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtypxgxahy.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtasddukol.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtbgdecniq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtypkwdwom.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtncauqdaf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtfqmwmjzw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtgtofqrjg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtnvtkzmoy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtcueeljpn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtsdjqnrsl.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gteyfehpdz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolnodnxm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtzmhrzgfe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gtlnnlpqox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtjwdjinyo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtsmpnhrxx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtovwvljoe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtzumyjvja.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtoukodzmh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtpekxsxaj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxqynjjyp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtqccjnuzs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtyhkwbfwn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtwdqwevxg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtckyyngrx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtbovtfxmn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtpcbbbfya.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzlodwspe.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtcfoarvpg.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtsthwpatc.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtdsqldqss.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtxeunftvy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtkbwgario.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtmllqdeew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtvqfryvcn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtxfzpruaz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpnhtowt.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtperlskab.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtmphspcwc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjfzkemp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtbolphydg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtlhsntvjf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtemfxoavs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpamxfsfp.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtbilctysw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtkgzlkijf.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtcyedhvlw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtqcmszoeo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtekvohdvy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrypttdqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtnamhjepf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtaypowqar.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtrihsiujh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtbrkvatlc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtwomrljbm.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtmvnocgbt.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtemtyxztp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtvgbbzqay.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtddofpgxw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtyyrtfgxx.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtjsdriasf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtxvoiapva.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtqouarnao.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gttrjyrtwl.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtpmnbmjte.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtmixhsozj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtucivjfvf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtahnakklc.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtuxgcnpyl.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtrhlpndns.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtynkuennx.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtzkjuerjj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtvqtgbven.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtydnqdyzp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtjdoxxynt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtmfngzxsl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtthvabzhu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuizacfi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gthfjremvp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gthmqqycwo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtwmjtrfok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtwkqurpio.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtsolzxilz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtyqoyolzx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtfealiati.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtaawwgiuo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtdjrqxloc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtyngrkxcb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtmgggblek.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtolejzgkv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtdftehzlu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwqvrzhbh.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtoodixvgo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtolfjlcnz.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtbnkasadj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtulnafton.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtpmpobgep.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtpmomzybr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtqhqaoxmf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnsmbuom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtccnaiuik.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjxetmfrg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtexexigfc.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtvnxbonsh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtzetvidrv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtnahejrho.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtkwcvsidc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtcyutatjm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkcteevx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtfjzesckf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtfjbatsgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtekmgxdip.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtsoqmwgze.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtyvcxrabx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtwtqmzkdn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtfwctfjec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtzwdsiwmy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtoehqtyne.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtdpqawlvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdmgtoutx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtgztairqo.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtkphlwecy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtqlbouvak.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtibbcybqk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtxzauawsa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtmkapocfd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtvusyjbiy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtmhuqtcaa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtljvagcjo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gthfmbvtkk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtipjvsujo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtdldaullh.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtytqwjbml.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtzjlydcjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqylsbrvv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gthzohcrrj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtfzxvokzq.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtclvjdain.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtogblwofo.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtafjwhxch.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gteajfosmr.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gttkjzpuhh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgcewrjvu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtouqxaudq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfbxauep.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtipupnfdo.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzzsdagjn.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtlfmdcalk.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtauoajsba.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtqhpswyxn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtbudkklvt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtlkdaacof.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtrckcyzes.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtrfynqetb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtmhephjde.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtqxmtrpol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gtawtljapu.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gteswequyr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gtvhmhsrdt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpryhpzqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtxbljfren.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gthnggygjn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtlgjnmbxf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtyxavbcvb.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gttocadjpl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtjvjazhar.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtcewvhwpr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkqfhgucy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnsowgakl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthheijya.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtwaqbeket.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtzgjkrooq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwdeekcw.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqojikyju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtfxbqlniq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtutzdrfrm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfpnscpia.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gthdygkiif.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtdyxjrlbo.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsofwswo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtmntwvmfm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcmuscsqe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpgufubk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtydnrqbxe.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtfjgmqzbq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrxuxijvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcmdkhggs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtgkqyiwyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpnkylgbf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtshpuahcg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtvbexpdse.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtjrjnnlpt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtixrfukbc.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtufboyxvy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmejbasqc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtujbopxnj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtnbhfrcuy.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtgjzbmaxb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtiyxhhxup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtnkctryto.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtsodgltgc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gthwamgium.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbztatlrx.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtvmkxnpzz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcemmedal.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtvztnyluc.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtjuqdaklc.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtoltctnps.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtnhzlwlks.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtufknvbka.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgzvwdss.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtvhnxmyev.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtchyfirmh.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtwemabsvw.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtylucrkin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpyjgfhs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtsjwrkmfr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtyqecvwzx.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gthrbfqunl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtzwbvrano.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtlcrrhrnu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtnworlwkx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtvseptooz.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtvefqnzfo.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtuswsnlmw.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtbqkvupba.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gthmtgebgs.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtwujudwnp.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtlvucihag.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gthavnjmbl.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtrskatyhj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtkwpbnfbn.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtpeetwazj.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwhmpqqn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmjwahzcd.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtcjunhidi.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtlhsjytmi.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtphfjbkja.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtofbniion.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtltgicpfg.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtwhhcqojq.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gthtmuqvjv.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtehadjxzj.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtacqssyqp.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtqorbsuus.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtezkaevnk.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtutfepizb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtpmbeprud.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtvgfwbgih.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtjrymkldl.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtjnovljfd.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtbfprotmd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnvpbrlfn.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtndjvourd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtxvatxoyj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtfsqyovvh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtokpwccvv.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtxxifoomh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtejxplzvt.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtstblqjbu.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgpmcegt.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtnypqndvz.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gttjayspfz.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtoewygkbd.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtskwcnnjg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtnjmqckgf.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtmicisskv.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gthjymdous.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtgeptytgi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtfqzvhrfx.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnzhprqb.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtytvcivgb.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtbdzwfswy.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzwvqfca.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtagqelplp.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtswcanefp.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gthrtbgiuy.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtrjcujwaz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtobzlffiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzetrfuen.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtqqdspnxm.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtxmpvolty.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtflvtcawh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtgwnztuuj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtnggflycc.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gteqrfgsjr.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtafkqjvtm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtmhjcncrz.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gthgbbnqag.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtuwkotwly.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtdhtqvska.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcwryxhr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtefzkyzni.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtbsrtpjhc.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtevttohwo.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujwhljsx.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtsikspbhj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtokqmueje.html


<!-- 参考信息 -->