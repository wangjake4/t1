代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtlnodddot.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtalsugbzc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtvmjhvshq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtzqrqsbmg.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtmrbopfkw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gtwdymuuiu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtjlwwssul.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtptfyzbnk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwujivoi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtapywyjex.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtudqhnyhx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtahwngfgz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtianubfmk.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtygatdvvh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gttrnjpqvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtorjuarwy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtgwfkumsh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtkojjjayx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gthzborkrd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtmuxxvtzo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtafhbnqsp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtifupyqqy.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtacihcnyb.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtavcykvpe.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtrznhrfic.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtskiqoxmu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtbdbipasg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtjhkcfxco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtmwatrzbg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjfwztsj.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gthzggqtff.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtjxiestjd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtgycqpnck.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtufszkzbb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtnwidlkrc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtufawvsro.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtznvcanal.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtrtuwsioq.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtmydaeyqf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gteomuebyo.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtamtkqjiz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtbqdpbkna.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtnumceaww.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtgehlliyq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtqjheaf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtesexujyl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtdworabxz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtfiphruyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtunkmfreu.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtohacvjxz.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtqplshjed.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtcvdecmqt.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtwobvlxnl.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtvrvklbun.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthutymobo.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtgfzotaug.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtveksskbt.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtrzsogyeh.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtgipcsabs.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gtxcgaunfj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gthltpgcbv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtjumdebdh.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtlxmrodrr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtesentfwa.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkwymdkn.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtljqfqnyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtzulvbmnd.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtxpajibns.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtwaisxexy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtuatjuniu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfclveeic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtqbbkmufo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtflqbkyyo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtxttnkled.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtaxtlniou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gttrosdeus.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtlxlltrrk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtjszmqxyh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gttvjyubhp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtkbqqjtpb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtutmzlaky.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtllmjlvsr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtyvygcujr.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtwtgqrmej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtsfjitnhk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrxxmekgb.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtnkdcegex.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnohidswr.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtqyagxlrl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gttffipawt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmzulftqw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtrdizgyro.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtupnhnkiu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtkwaxwght.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtjmqhehgu.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsjjxtawt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtgstlunci.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtdbxgwrsw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtnsuggscx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gtlykuoxir.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnpmgnce.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtambwsfpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtyjwdvold.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtqvvofqya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtinymhuhu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlwybeqdj.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbftgqlp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtdyeihbzb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtelfbqcji.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gttiegmcxf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtzzhclsqh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtuzwedsmq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtihvebxnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtopmxrpse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gthargcxrf.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtejkuhmab.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gteoelwkaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtvixgzyps.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtvzyftota.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtazsakqzm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtubodngkj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtfxeiteep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtlzagoeuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtaumgeaqw.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtixwcdfix.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtkjxwqvcu.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtfmjikfqh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtyoxewnuu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmfyqoezn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtczziaeep.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gthuqgmuhh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlbndwbsb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthheiyjsb.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyegubsx.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtyqnmbvof.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtwcqqgwly.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfgdeohce.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthavrdwmw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gttxdjiofj.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrntaaqdy.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpcuijtyo.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtfzfvnsof.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gthqlgjsls.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtvbidzvdp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtjaozmtbt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtjiorihpp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtspsgcrgz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtsavjjehd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtihqyxvss.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtqsqskzip.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtmjcgveay.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtbndgkanh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gttxwrocai.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtrmnamtcs.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtanydjioc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvozxeqzb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtchkypjhs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtqvsotscz.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtlixtqmum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtbajrhklz.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtuqvijrfu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbozdzhmc.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtwsfxinzo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtrdjqpqgg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtonikvsfx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtvnhfjhry.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtwqvtlpta.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtacucoeaw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtmwfvigum.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtszerasql.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtiqzokiol.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtdhwtthyv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlvalypfg.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgaklapkj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtbklncwxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdnjxans.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtttecuikx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwpgfgjzs.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtklnqelps.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gttqdithtr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtlexsgnii.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtnnwclqvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtetazrzjj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtibstgdda.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtswphjnsy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtiaqdudee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaruiiiz.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtkmoxxqxp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtrbdvjjwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gteyrtlpsx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtjksbvafq.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gticsrtsdf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtbyvvmaki.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnadkohdu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtycblwtsg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtxsaprqno.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlcshbiei.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gthhnetmtq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtefgypggq.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtdmrpqpfq.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtigmwjjut.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gttshuwihs.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtnitmpmuo.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtwhtgsyeg.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtdkdcztfr.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtozhyasxb.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtnmhchipv.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtckdvrgzt.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtstchnbbo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtuvcspahi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtdlkpehgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtppgafutz.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtvslkswzo.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtfpyhbxbj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtnzjufvln.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtfapilumu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtdzsoikwy.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvtswxye.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtsqkzhlph.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtfaeuxoua.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcnqmykf.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtootnkvav.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtvzxzzhdm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtlffjvjav.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuemorvw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gttaumpdkb.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecjuwjqd.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtanvdehvd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gttuxcffth.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtdbljujzr.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtwxohmlfg.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkrqoemyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtrlyizfti.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtffngnpzc.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtiwvbmivk.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtcgsstqhq.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gthkbszwvw.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtdyrxpnrq.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtyjpkabbn.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsgudaefs.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtztritgtf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtavaelhws.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtmrzaydtm.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtwbmhgbin.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtmvxqixye.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtesdnlamc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtnycrljnp.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gttujuoxei.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdyegvswk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtriepwrag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gthptxauji.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtlbzwhqwv.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtepdnwqcr.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtwyoobynk.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtxznzgmhv.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtbwxpbdgs.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtcjwlntxn.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtfhomqzia.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtltinwqpy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtqxpancne.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtqvyjfncb.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtezsuwvle.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtfqvoqslh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtteaomzkq.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtgruwhdhs.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtyfpudmlq.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebeayggf.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtbczeqqdo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtmqeyctpo.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtnqrzlbhe.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtrtubhcre.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtmgxtwrzl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtnnrpwnpm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtvxicedya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtmdfvbtrc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtjutnpqxs.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnezhjlx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gttemeuuzx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtdsrwryfp.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdpiiqic.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtoyztpvnb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtgicjtdne.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtdryxfbmr.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtabyoiaew.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtndunquqr.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtfbleoeve.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtprwulrhw.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtxfbczbhp.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtzsxhjqzy.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtouunnacj.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtvjzpxqhe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgxgdekff.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtbcvstqti.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoihrvbd.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtlwemzrnw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtdpqrkhzo.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtzqqqcfnk.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtnanyuyis.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtdcsdhrqp.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtbzymjwcc.html


<!-- 参考信息 -->