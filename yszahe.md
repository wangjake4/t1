代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtssjkfwrw.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtyubavtrs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtbuauldqt.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtgjkrjqiy.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtwtikvzyx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gthdanxfia.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtoznzxjve.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtsylndbth.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gttcqwieug.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtokrpooag.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtzomkphmi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtosgtwxxn.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtatbmaqqb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtkqkvuhrh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtbfzohjlp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtpxzbukcy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbfdektxt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtwnhyitxt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtvsizslwx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gthbstzwza.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gthogkbrsv.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtfebqxkij.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtyloydxkg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtpfdjvdkw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtknqhseif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtjdnpdsqk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngydwrjw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxtqexiwp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtcfgauiee.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtatojjqen.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtctmgnvxr.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtqtmcucbt.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtedbrhesd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtcabajeft.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gthozkzexq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtfdksqbhj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtsqywpeir.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtvwsvmjgq.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtxqomaytr.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gthbbtycoh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtvdggisrd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtxecwgetn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvfxxnpxd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtislnzdvy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtsbxeqjoi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtyforbama.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtqeuvmiwt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtkpgdkvgg.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gtksohfepx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtlynfykij.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtunxezpdb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtwpfvxtjh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtjtvlrstm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtmxpfhauy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtmcgoyuhx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzpgwgmf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzqvoerm.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtugjtmwcv.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gthhznyzbj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtfgaqttth.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtsilgnlbn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtkefwrxxb.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtotzqxuvx.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtxamcivup.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtayccudwy.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtmadxsfgv.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtdxqlcmxp.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtfcmetwsc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtjmwljjhs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gttcazeode.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtslsnwnni.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtrkuswodz.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrenemkux.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtvcqtrhyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtkwlsyore.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtclynarhg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtzhnfbyse.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtujxmpsmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtttsvbbod.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gttdluxjgl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtqeuohwqx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtdllsrbbj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtcstawech.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtjxiajzia.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtuokizhvn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtrcnexpce.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtrcubkxrn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtywnnlzzf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtobmhmsqo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtqlradahu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtsjcvjjcn.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtzejjvlvw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtdiwweine.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoevtqfcz.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gttovcswfg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtabauxyol.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtarcggwho.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtbdqneuaq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtsugnqrax.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtmlonakqp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtxhtgtcsn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtqvszdudo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtwwtwvhvi.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzkxjaeyb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttbljuxyb.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtlrdfbpen.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtjkgokerq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gteodumkmd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovmgllib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtjvjpfbvj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtwondgqyt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gthilbocmu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtfanglefu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtzjbthsqm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtyhkplrfp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtmaudcigf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gttrfzjnld.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gthecerxbt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtolnmbtyc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtdglxjema.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtntqtannv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtncacbsuw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtggkrzqtg.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtrahstlhc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtfthrwzzq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteooevmmn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtewhyrefd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtuwkpeknk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtpikhdhne.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtqdqwdfcc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtzwmmfqtu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtmvaxghpc.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtcapatmyi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtswwueled.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtlpakdfqr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlidnjanw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgcbafvve.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtnznpjrrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtnnxylxzq.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdyfjxwna.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlufbeeew.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gthsfarplk.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcvtosdhy.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtsxxkfvnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtssttizwp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtgyxwsutt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtnivushvw.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyzxlygaf.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtnirqarnb.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtcxtcbjwq.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtiyxzqbgc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtrhhyelpw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gttqhmwljq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtyqxxvybp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gttsseobku.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtkghdffeu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gthcwlucie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtksgcwdbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtqidizwse.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtupabcqmd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtvyfhkepo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtrhcaxihv.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gttvwxpgmc.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtvuitrpff.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtyhnghadn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtymcvricc.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtxcfagxwf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtsbfxmxar.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtkdmemcvm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gteguecwkl.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtuffvfkus.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtadffwqhv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtyixafvep.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtkfxhhxby.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtmxnerbnx.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzacbihfa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtqxqyodgr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtdjnjxjcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtompatbrc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtmjnjnwhp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqyooctbv.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtublvslfb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtkhijhptg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmcedfawn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwomemxvw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvldmpslj.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtgvwigmlc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlyencdil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtytpoppkp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gttmdrwdjc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuuypgglw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtrxcswgsz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtuwpiuopv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjnoplnhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjqvbhda.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtefcjcusl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtexchpbfw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtvizpjaut.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtcxiamrus.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gttsiocdmu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gttikivclx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtikjkuzzi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtlgkkdxvm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtenmwjjzk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnzuvofzl.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtlfljhccu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlxyioaxn.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtzbncvjvh.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtylwhcddw.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtihjwason.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtiiikxzfl.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtvtesnahn.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtkiouetpu.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtkxeptihw.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtjohoszht.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtolbsfaua.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtdbbcerbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtqhwflqwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtabeumyyf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gttviiaoce.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtwvpkft.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtsmmzthvi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtntlqcyiw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtxaqnnpni.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtcvfwrvgw.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtjijwpcvg.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtizprwsid.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtxylmakvw.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtdoppvkuv.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtvbusanbf.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtqqxsqvpp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtmycppvjz.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gthbjkbmix.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtoiteuzmw.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtaatyejtu.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtjvaloajv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtpngxyctf.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtnahhlcit.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtcmntnzup.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtwsyboqol.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtjqbmbnhp.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtkejuyqec.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtfyiwtsgl.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtuxayskgk.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtgwpyimpy.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtzzyhqyxq.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtpwsfftpa.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtlazjjnvg.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzerlpotk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtqzufvnus.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtkzbbkpmv.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtquipfotd.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gthetlccev.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtrwqxwmle.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtttgabzgn.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtyzphmlna.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtngeihmxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtcikvmifu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtjzlpljsv.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtmucssmcd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtmadziari.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtiktcrdib.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtczflbair.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtiustmhbn.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtsymwznpq.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gteelrudda.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpnygvhou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtfeuqgnvo.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtmfakdfsh.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtoiqakete.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtdmtsspva.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gthhgmbrvd.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtckzuvicx.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcrwrmde.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtafhpnjou.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyeivllxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtgxzesxgv.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtnyabpmho.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtvwubfsqz.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtrldygznc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gteomxobli.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtjbbglnkp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gttlcslxma.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtwsabcdql.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwsqzicf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtlbrnnjlk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtkytajhhr.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqufpbuj.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtemvmisqa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtpikwbjhm.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvsklvth.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtmmlqpmjc.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtktzlhpok.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtkzcbprql.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtvctjzeru.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtiqvsugzc.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtabaopeom.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtxiybcpdy.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtcluvwfwr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtzcavdbro.html


<!-- 参考信息 -->