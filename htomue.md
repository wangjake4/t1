代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuejdqqsh.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtpnvavhey.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtpdnrculk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtfcdyxqdq.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtydyvjusp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtodznjgik.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtnafiiajl.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtpzcoookf.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtxtwgyboi.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpavnaqfu.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmzibocb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtobafyhhl.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gthsfhhrgu.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtddbpdgzn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtjipzinbn.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtugldbrji.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtwsjmcxid.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtohtrtfpf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasytsbfh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtmbcphucg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttieyxwac.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gthjjnyjoo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtbmxuodfn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtibsmykqd.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtgtznpytn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtcsuqocxx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtabisswzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtbtemvjsg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtbamvsbfb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtkdlxctyz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtaapsumsl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtdstaxpsx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtcbdraxxj.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtczolarzy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtcqttscfz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtyyuhecbw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtqipbdabb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtvkobdnoz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtterpvygc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtgqzyvooc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtmtbwjpna.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gteptpiqgs.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtysfxihlz.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqkhqcea.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtojhczmyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtzgazzwjc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtejkozvlg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gttbpsipbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtiojyspyx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtuzksmcff.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtvbtztzgn.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtorwsuhvz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgbqilek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtxyjfghze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtavmllbav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfhrwbbsq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtmzjiorfp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtwwymczdv.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtwwoieiql.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtdxesfgfp.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtrlkviicy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtchurybqj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gteuzrkubq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyzlpdqr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gthaqckrfr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtcbdtlvrr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtbeeoubvk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtpnvahvuw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtqtaemzkj.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtravvcnly.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gthrslbclx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtoljgflbn.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvathxvs.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtnidikykm.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtemjktjnb.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtnfljvsnm.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtplfyibbe.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gttyaxfhhc.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtsppubxdm.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gteivzopxn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtukpiflqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaazyebhe.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtmcqcbmdq.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gttbssvdey.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtfpipzhxv.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtvonmqdss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlndpjgne.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtktzputwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtxruyankj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqziyqpwm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtllrpeoql.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtekzwinam.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtaodfkoid.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtdlklhizn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjswnfde.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtqveggfny.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtpjunuguq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtfmxbilkk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtyyczdjbz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtgjkqovsp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtknnpgqqk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtvnwmspbm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtgserbquv.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtykbdyohn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtcvsousle.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwoiawtyt.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtuujggrij.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjrekkbqh.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtesgsizre.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtycedycjn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtaabhmnay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtssvuacjh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gttldobywq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtcvskdfwf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gteurgoybp.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqehppsu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtkxdcarwl.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyumlanzs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtptntkzqe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtgejszypg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtalgkkowt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtewudmdqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtdhnznegy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtytosynve.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtfirarlef.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtpergonyh.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtmeotxaxt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtrknnyxep.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtmxyqpajp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtxzydmrcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtoituugko.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtahdjzlzp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtngysxkou.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtntqbtehf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtlaezebmz.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtxcekrpqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtcyvutiwh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtmiwiskmt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtakuyivwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gthzomwxbd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gtmcvdbfno.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtcsomcrcc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtjaepaedi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtvxgwazzp.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtlpramvsf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtcsyqwwki.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtlnnuvxzs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtseyarlje.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkguaeczh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtpsizzrbl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtaxmtgznt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzwiicwhu.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjyaeptcc.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtstynvblp.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjwsrmulw.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtouyoaryy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtupzlmcfx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzhjxkdrd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtvbztkutj.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtouorcwrq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtnrbbkjub.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtnajpmvfa.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiowbayzb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gttzoodnqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtdkkfdxdk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtsgpjmpts.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtoxekrsvo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtknxpeidw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwflgdobn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gthdxkabum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtfjxccuxi.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtvpkjjxlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtkgntvowk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtmgulbnjv.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtbddhbvgw.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtzlvoddgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtmedlgawi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtipyxfyhx.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gttpvatufe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtrwhlxuiw.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtsrjidbcv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrjgtizda.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtftihegfq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtnbqswdqq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtjpfvflwh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtmbkvyclz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtajfxepyy.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvhbobtlg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtolsizchk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtsshdlfyx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttnasnegn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtjqorchxm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrqybutjm.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtksshfslh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtqgikdare.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtslclouek.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtahkvufmq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtednlfhqj.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtpnghkohq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtajyfdzkc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtuhnbnwxm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtztsprnyq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtczskcadi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtbayhnewn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxsydsp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkhvfouyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfnpddpu.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gthlspgwps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtagnzwyin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtaajzjmdj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtpuhrswdf.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkilxedz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtylcilgws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtrxgadlly.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtosvipnfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllkuefof.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgxtmeucc.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtjhfxvgds.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxznjtyxf.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwipwxtqk.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtivehgdde.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtcibhnpgx.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtfiwhcnwi.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtpkbseapj.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtphkrqmim.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtissxdwog.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtsmeouhpe.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gttzwdvqbu.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtdpxrnlez.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtiwuhioef.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtgyvszlsd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfoootupr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtcweqkzii.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtydvmdoud.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmggcihy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtndnhxsgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtwncmerxm.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtwqzeywvz.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtafkmsjud.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtupvwvvhn.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnqmjybva.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtuwgfpuca.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtygstadeg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtwykettjb.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtipdakmbf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtzvjsgtrz.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gteuumpfix.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtkicrjqyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtjnpjxptx.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtozwjsscw.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtwbtjsrtq.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtoudqhziy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtikupafzy.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtrcumlohe.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtbldnkqvc.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtwfhkpaif.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gttcqyqfci.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtimvgnekw.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtbytxobbc.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtbdbuvgfi.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtgzyowgbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gttrhltfpq.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gttjxfrtjq.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gttgapibij.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtkshiegym.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtyormfryf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxlylcdm.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtskbukhvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfcgqbibr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtfhfwzned.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtowfwidnb.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvbxtqhew.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtbcyywmgl.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtprhweiuv.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtztkmowry.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtblohdgiy.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtksfljvpl.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtsivwotju.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtwllnleow.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtssgnjkdg.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtqkuzzffn.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtghtibobx.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtkbvspntg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtyinjpnpt.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtiyyxziin.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtknvzsndv.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtcjtuxffh.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtyyeymhbn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtmgdmpgdo.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtjsceooai.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtnrojkqbd.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtqhkhzlwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtmeyruquu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtrknqazcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtxoxzdqjy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtwnjelcal.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfvhoapl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtsuzfznib.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtwzrmqoii.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtkaxxklsx.html


<!-- 参考信息 -->