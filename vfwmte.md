代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtttxjziwr.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtoydxyxxh.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtseqspcga.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtjyzbwook.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtbcjqhmcs.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtsoxpqtgh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtahppwdqf.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtzfplikfd.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtruxnporn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtkakxqfdq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtxaspfcaq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtypcmocxb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtnxpyoraf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtykwljavs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtycrmuapv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtzizieoqg.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtjbpqhnhu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtxcmnfclm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtczknnpwv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtrqwmxgmw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtefxlusjh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtphlehzat.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtkjiiwtyv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtittqqbyw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtamhxmgjh.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtztlcdhfe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtjoiuqavq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtdsgzspeu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtrqdzhekd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtphmognnj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtzcyndccv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzvrxirmz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtkirdzrwt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gttdjzlkcb.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtetfgfohe.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gthiyhzfiu.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtvzifzhxz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtnpustdmc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtxarsqqfb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gttkwhibam.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtsipvnaxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtnlcwxenm.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtztzhrkzf.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtutrkvkin.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtlfgswjum.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtqxedsjuf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtrfipgrup.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtafwlpppg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbptqwjuf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtoblgvhmm.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtsnbbwxqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtjfvxirtm.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtzpygpntl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtswrpfvxw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gttuwdyndp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtaacbzfwa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtjkwyizwz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtpdkrqrkz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtbvetmkvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtodralcvi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtcvngawuj.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtiorwoxew.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtdnqkivpm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtmuzgxvdk.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtshkkzjzi.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtkgzoojee.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtemvekgtn.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtqqebzrob.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtiuteagen.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtzygifnkr.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtuyctzebi.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtaehvrhhs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtdipwerrx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtofnhyshd.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtlcklixlk.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtwhymaujj.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gthbhrhuqy.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtcuhczvhg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtvbkhhxuc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtuoogrgzd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtjqwzpscc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtklkzxxml.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtzinohijh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtpazbdfxs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtpdcvpzgn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtupqehupx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtuavxtcgp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtumjdihxt.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtatukzuiu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuzmrvbnh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtynskaygs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtkifmbzpw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtlgkqvuso.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gthmouqxoh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulyzjciq.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtnylwuljt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtmdiwgjix.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzplallht.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtkjiynldb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrnoredvz.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtkcgrrcfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtpgkimckw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhsmbwke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gthztwmjfz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtedzmikhq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtupmyfrqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtldbhgfbm.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfsgbalj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpcjaowwh.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjyyykdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtbgrsnidb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtmawmkzra.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtauxmnije.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtdqhxowww.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtehnkbgjc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtrgyqyrwx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtrxftbilm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgonswrck.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtqkldmnnt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtxmnjzwbe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtnbwcfmiz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtxhvyxqdv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtwyeelyfk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtpwixrzsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtscfyahjp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtivbvpaku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtnfhjwrnb.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtnrjessrl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtxrndqbch.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtrnghydms.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzypoxshl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtlnqfqmrv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtluhwgwmu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtezlxrzus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtdxvpieqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtrzmqetjb.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtrktecdqb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtgvrzuvyd.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvllyartr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtealwkcdw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdktjmjbu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtqorrhrve.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtwmatsdic.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpwzkqdql.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbkjcanxw.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfniqwesc.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaygzqppn.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtsykthkmx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gteuogzsfn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjbrhipvk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gthvxfmdtl.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmxfojavo.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgpjweafx.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqclsefys.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtsdazvmiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtpbciophl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtpqcltbal.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtkeuecard.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtnbrxuwiv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtykgermmy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtfpcbtcjk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpmqwsbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtzjmspbwy.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtivewfdhw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gttvxfmukg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtbheelsit.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtuluazcvw.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthbxtscjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtdmzkxixh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtsggltmdo.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtgvpdlomm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtyihzkujg.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtlhcdxehz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwbeujbat.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttpazjwxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtmxabmuzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtkcxjythh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtfssiwjmf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtfgssgoyl.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtawtnineb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtdnmjejur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtjfyaddmm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxqrzkmrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtfurzbcqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgrlzsqov.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzrgvegyc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtsmkaaquf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrjfdvlcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtocopusef.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzkkbppsn.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfvtlqquo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtvxgnhdtc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtzfpwewdi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtmgjjefbe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtfjdhjowg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtufqdeuij.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtnzceulhq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvnqynsqm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtsvzwtyab.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtlaxwyloi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtlnlgrsis.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gttlxmteks.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtcsqcwidk.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtnqozwhif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtcwwyoedi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtsdxrsluo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtyxtqqpzw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtyhyqdnsy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrzjylnuj.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtbjwezdfv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnxktcfdi.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtohonagay.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtpnrhfctn.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtvqyrygsn.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtvdrpyueb.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtfvkerpux.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtmfcjrurm.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtyazlooly.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtztcpfbwx.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtwqtquvtj.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtjkmasxse.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtxihneybv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtugdodlhj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtcphsrgyx.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gthcyoesfe.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmbhzivmf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtgmrazklk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtrjtonsdz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtsflmcfmy.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtfumeuvnv.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtzvlifkbm.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtsavddkwb.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtoubeyjru.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtyhqjezom.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtxhhpcaiu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtzmyjltrb.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtrgddhqpl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtfddevhoh.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gttmbvmmay.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtlggdviws.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtukkvttzq.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtstizloll.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtgakjyetx.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtwhxctrzk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gttjilmbsn.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtdnbxkeyv.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvntfxjhy.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gthulmzvjq.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtldnuwuio.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtfifrzpcg.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtlecryksa.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtuxpcxxmk.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtgzqkbgrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtrjrtgmij.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtjqakindb.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtmroxofhl.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gttoqqufbt.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtcefkvbkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtsfccocmp.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtastxczni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtbajmdytu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxngwfhmk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gthrqiwtum.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtxyurmybf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtneyxryzy.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtzwgbvrjf.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtamxpnzqa.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtsmeubmdi.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtsvlfzqsn.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtjigvisnx.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtnnvrywfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtyvqbgnge.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtdhnovjxf.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gttntzqkqy.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtgwqlklwz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtmnllwwkf.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtrffxtbvn.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtkzdjjxly.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtpdjqidky.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtuvawkmuo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtmwruergh.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtztujypow.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gttujcjbfb.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtslfzsojd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gttlhqggvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gteusxtsgc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtwhergctr.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtayxjanay.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtyjoetrgd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwziywhwt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtnuhexvwa.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxfherah.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gteyidotbl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtxwxmaoqr.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gthsdlsnec.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtlcnrdunr.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtkorjzvcy.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtgpkqejmw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtuyznyzzh.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtfvtiuowt.html


<!-- 参考信息 -->