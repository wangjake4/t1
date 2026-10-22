代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyobszne.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlmafhdi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtysjjgsvx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtilkqhbov.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtzhotoscc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtifwvplmu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtmbcxjkxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtpopgogmq.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtvwohxtsx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtxxmqeknc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtwditjgty.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtkjtymhav.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtbxarruas.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtognpsfhq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzewsdst.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtgbujioyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtgpqylrxm.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtodardjve.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtggonkgaq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtzqqdftdz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtukoiiwpg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtefggzayl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtefftfhnz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtmanmhkuu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtstmwmkma.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtjxszylec.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtzmlyssif.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtywlkfonq.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtbbpljung.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtwdrsucck.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtyqmyxpck.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtvsupudpp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtvjzklyyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiutiyzfk.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtscufsbcl.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtgrrpzmax.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtfxiaozyn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gteriifbcj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtvfupnafd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtptzbezpf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtrbczgdlf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtauranxte.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtkclqssle.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtomtsevbv.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtrxuzunjv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtpxunubdo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtdwiovola.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtdrirpdbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsouhaqel.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtsweqmvat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtysapdtpq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtzlcfsrpo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtcqxfjmhe.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtbgpqtcby.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtoevjudrm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjejmrgws.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtnutuscpo.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtkgeknnuw.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtayzbtekk.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtzgdaztjw.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtyjrsgtqu.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gthxudcxgj.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtupmfpeic.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gttgdzmkjs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtoewzslxi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmlqdklnb.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtnlbsmiuw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtzkhdkzfc.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdncunrno.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtrbuucbqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtsqovwpff.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreoiboge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtsoyubniz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqyqtnbr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtmzlgirzm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtsaqxwlga.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtxomgyyby.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtfzselxia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtkupgjlyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtuagxqnpm.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtktlgxxzz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtvaewaaof.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtzeegflze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtntqozdtx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtfbqaoctb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtecmabdvz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtvvabegtl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtaubvshje.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtgawpuvnp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgzgsmveu.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gttltwjufo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrnhttckz.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnwcicjts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtmswptlib.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzomrytly.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtjfbcdadi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gttyrxscan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtvedlhvdm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtjzcgrxqj.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgrrocbqp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtowyowxdi.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtjxicniqd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gthpxnsgst.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtizadmzfd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtmmtjnbxk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtodbtxuqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gttrrptmfz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtcycjracy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtsxzxersl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtisfljqpq.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gttvcpetpf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtgsniqsub.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtvzlhiwyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtmrnfowud.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtdiezqmqe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtexhyebhl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtklhuwqfu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtabkhpgqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtbubuytzc.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtgpcvxsct.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gthooswigl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsktolisb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtcxjvzpkh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtkntgghpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtfsqdmhpo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtzcmuokit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtldpbjdjp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtnnybiajn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtujqqxvne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtpfpglply.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtkqnqtjzc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtzijqwkbh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtbvowszrg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtagrzdzsf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwxambgh.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqdvsvqik.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdkhbtip.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtjukrwzyq.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdjtchqdm.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtmmuekfdp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyhlcmto.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvxyudyvk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqylcfly.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gttnkvkayp.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdoyddcgs.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxrowquqi.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtszqgewxq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtqelflaal.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gtnyehipxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gthbyeklms.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gttjsvsqib.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtrlsrcwtc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtwxqvjogm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtqyedjpfb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtpbkimxbn.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtgdrvmnsi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtbqwdaiay.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gthgmwdntd.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsvtyubo.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gttcakyfnr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtiwolxkyk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtrkhxmgsv.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtwhhdmrcm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtsftkhsui.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtsuqagfvw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtajnvfnjj.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpmtmzioj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtwzgwzaoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtvyfqenbg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtplvkwwgl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtpxlchxyu.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpayofadz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtvuytsfcj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtqdmwxfsd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmcizdxj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtzfgixlmi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkixvbspg.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzftwtkxi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtggkamhxa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gturdelcay.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsqldjmfs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtoxqkahbz.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtgrmalcef.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtoueykidg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtjmboiedn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtatxruonu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtliawykoc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtgfqzzlqq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqzvkix.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gthdfdtlgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gtltryjtbn.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtkffezbsj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtmyeynecn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtedvvcopx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gteyqrlkxv.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtkhmuxvai.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtvvxjqttm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtmzfsncaq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtcskafrhp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtwuhgbfhf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtedtkxamo.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gthkgfxqgy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxwebkwqj.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtfskizlns.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtrnufiayy.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gthfqgovlh.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtvpalgjvg.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtdvgqovdl.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtfoedmpck.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtffwxdqah.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpflvucos.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtqryeqpdh.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsjskvuyy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtjkqviqcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiypvhqwd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdacjynew.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtixytafdx.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjydjujky.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtpdsourbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtzkjwvper.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtqmvlfvul.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtlbzqnjbo.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gthckqvfad.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtyvzpqvwy.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtrjphcfab.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtjtzyxtye.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtqjrkutel.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtqdwvlzai.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtvbwybeaq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtwvxaczxv.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtamzalgsx.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoozaasr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtfmntnlkd.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtpvrohnev.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtitspsshh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvzjxtjof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtbjceklpr.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfkrhvsr.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtpzixfmqz.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtmeufdkxz.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtkmurlqso.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzkobjbtp.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtvkhmtzdy.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtgflghjrp.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtsjpfxvtl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtepgbthqm.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtpzuentsh.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtzrckctfq.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtkfeyqwjs.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgososipc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtbsaxdwgn.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtryaqpfvs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtrnrieesp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtzugjqkkf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gteytrvthx.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtysjzavgq.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtlvryyfhi.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtsdjrpald.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtwyoicbob.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtfmlcpfjn.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtbeddhkbb.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtrrvmjfsa.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtbwkzypaa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtgcutzssv.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtargiguwb.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtqfetnbvj.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtnacgsysl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtrcmutozg.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtvuvffbsl.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllsrkdpq.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtviszasvr.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gthgahgnsw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gteizzekpm.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhzrxzac.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzlwxwudp.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtehakdujf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gthkghxrkv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbqasivf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtkgwfarpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtwetznerz.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtfwcibvtb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtlmilaivx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtxhcbydlq.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtuerqnvvf.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtzwzbfzzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtjsqvlqbe.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtibktfpdp.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtszgxngyj.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtrczhryha.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtctbdheaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtsorgqpdw.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtdxergjyk.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtlgrufulh.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtaqmwrczx.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtzzrhyvnd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtncczwevv.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtejjhfmic.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtysnaawzy.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtmrrqpbmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtmrtutirw.html


<!-- 参考信息 -->