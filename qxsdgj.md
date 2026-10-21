代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtjhtgoinj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtgtdqucln.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtvuqxldfo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtobctwsxv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gttdmcccwa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtavspumxl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtplconegb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gthdvpwnjq.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtykcrihtz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtvdltsbdm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtdhxlnunx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtsrkyatqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtppodrybv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtxzffxhqq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtbwrmxdir.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtymikqfvj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtdvkeluym.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtezmucqwk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtqimxlarf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gttvqlsczk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gttzofacyi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtlpcldoag.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtozgnhapt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtlgbsevew.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgxwnltqi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtaelxescq.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtlbzeeewn.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtpmxipomm.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtgqorqahw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtodnoarnf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gthgjgeovb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtqswxoisi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtimwwzqky.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtbyybxpet.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtvimoekfh.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtcfpkhvdb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtpqvoniha.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtqpooazyp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdymmunq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtjqbwrolr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtkzyoflyr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtciovhfqg.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtwpexzalp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtgcrjmath.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtkehdkddd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtwfwkqpmx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtqvmdtuzy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtaqfhnnkx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtzbkaovoi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtxueghcem.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtbyyvywid.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gttegskcnr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gtkfqbyxcp.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtgzdftjkb.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtctbrvwtz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtyscfqbos.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtrtuoohog.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtjhsoniug.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtqywcunlv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtbfvmokxo.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtbqbboifo.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtrortkuqt.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gtmmflkiqj.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtbnmhwtdt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtjxotuowd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtsxpuwpsu.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtdgzbnjhd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtaflhhgmi.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtychmmfkj.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtreuiwgqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqgrxtlor.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gteflwwpgt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtpwibwsxl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtvabsjyhu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtmyblsfns.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtngqzoaqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtbsiqhisk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtdxsupqmo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgpmetdl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtrnsldafy.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtsinbpmln.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtxuddeghe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtdvxtcdnw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtwuukvdbg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtcoqsbdtt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtjkzimsxr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmphqhnoj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqgipwvr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gthngbazuz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqkludpuj.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtanhnsngr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgedgsxid.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gttmsyzbeq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtglfakzun.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtnrfprsxo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtiqjwzamf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtyfwxfxod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtqazyknrx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtjknjjucc.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfoblfizv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtezpbbakz.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtkazfzgbd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtuuoirhqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtzlobltew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtmzfynvfx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtubycsinz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtmnqlchdd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtqszanuav.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtthwvmckx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfddiols.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtjcugzggi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtkefmhwqj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtnpepymku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtbugvhgws.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtsmepanti.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gttguiytph.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtaxgsmhrf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtvhjupckl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtftuaejbo.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtirvlyxjz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtikzhsffo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtovpfngjo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtldqchtna.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtbptgzgiu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gtwxojbpoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxohawlut.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtnreupyix.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtassofpjd.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gthenizncu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gterblsixu.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcyfmlitj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbrtzwdze.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuqhpxdhd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtrjwyoqxt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtzmgksbov.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqdyymzfb.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzigmwjrt.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtkjnczbnv.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmufrlfbc.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtrqnfxtss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsdrmmzro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfpqognkf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtmighszgl.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpiofmbcm.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxpakfhcx.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvjmnvjkg.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtjwlmgnvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtunstxefj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtsfasqcsi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtmpeicsly.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtebfjvvdc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gttdqvmeuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtehwxwezl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtqrroygbt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtlnqddjoa.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtrlfjqrrf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtsupapblt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtmzufdxbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtbaqpsuwg.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtjxmudquu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnpqqikg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtliskhbat.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtalpwbkjw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtrwjszhgr.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtscsmaqyh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtgbxfmgst.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnokoexnc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtoqxikboh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtryshxevo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtjjacnfgv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtthskhmqz.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzbaopjjm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtrnhlsrsl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtsqdhrebz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxaylvwjt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvulcimts.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gthypawfje.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtyfpfsqox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxpclcmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfzyodqcq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxbydlkfx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzqghezma.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gttovbmpwz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtufrgajry.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtynzvenld.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdkjynbop.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtszhuntas.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtbbyrmppx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtibcqrcpo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtghbzzjqd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtxoknvggx.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtoqgacudb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtsnfscrjs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtingoexal.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtpmlxxvof.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtxqodkpvp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtwbvwfxdg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtenhutsbf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtiluuqeet.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtvzhjecah.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtamsrozbp.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtvreakkxi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtufvozccc.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtwndiypdd.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtbjkocrsr.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtyllypust.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtutwkcszj.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtsfxxrrrs.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteevrzuib.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtxapkhksv.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttrhzyus.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtiabzhytk.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtyusmienm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtmbpjwyap.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtmdqhrrlb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtrdxzqali.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gttcsrvtbp.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gteqflbyjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtcojajojq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwolyjrak.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthpzsddcl.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtqllsoobv.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtsfwxgdtu.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtjnyccrvu.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtuixftjme.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtwochlvcz.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtbqxttjjl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtwehrvtvm.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtpmjzdpvh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtezgctwso.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtgwsniyiz.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtvndgyqvt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtcmdantan.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtvmluoclj.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoqjkngg.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtamrfwtnx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtopilbpwh.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtqejpzdaw.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtbeqqtidm.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtesyatjyw.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtpfcqumuz.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttvohhvns.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtdoxfwngd.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtluzzdrmd.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtrzirqvde.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtvzdlascz.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkwtrpkpl.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gthxsaozqa.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtujwoqohb.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtjdepbneb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtikvjnmmy.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtlxsxdmvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtogcsrcwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtanyamdqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtkwofkfxh.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtkqtmebuo.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtlpimhosm.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtkdgvmnbr.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gttdyikvih.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtndohnmhf.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtabukrarw.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtzrabwncu.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtmljnzthl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfryivksw.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtqiiixdqt.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtkbbxqxht.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtqztgoptn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gttttgdpgm.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtnbstnkfu.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtafweducu.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gttxnjjcwh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtcksbipnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtlhftycne.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtfgjzmobf.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtnhntsemi.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtfqulvehj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtwhbvjxey.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtihqygmlh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtpbhiwqiv.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtvqxnchpf.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtwsefdetm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtvjohipkt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtxdihdiza.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtwrxogjgk.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtyvhkclhc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtmclojhqn.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtbmawipvt.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtpkecihmg.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtzqpprtcr.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtpxfkqfby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtckqmicic.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtqqscswpc.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtoudtwknh.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtgdqkjfnm.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtaqnqnzro.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtadgmsggm.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtoxursoye.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtdriqtkas.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtkhpdlsul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtqvtwtocd.html


<!-- 参考信息 -->