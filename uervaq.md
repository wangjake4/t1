代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2isddjmxt.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2magagedx.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2jeekbyvi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2kcbvjctj.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ubotiabk.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2nzhmupnh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gt2ldjlglem.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2qelolldv.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxglahgz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2aqgzcxkx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2ghrntfvl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2juevtbku.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2oaisehol.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2wkhqqksm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gt2axetbkpu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2nmpwfkta.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gt2gebaeqhj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2uyfgowcd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2acaxhuiz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2yifaoalj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2qzinsmrk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gt2tcmtlfys.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2cgdadhhm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2jxbjsoqp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2ggxqbcav.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2hbyorbuo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gt2rxzrggpg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2isuczbkx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2xdjoropj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amafovwc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2oirphzre.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ocoztmys.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gt2uzyfebxl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2glheuupa.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpwjdium.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2ooauwvoi.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gt2ddjzobsm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2hewfivcd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2uwcvqwlo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2hpqqgukq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2qoadgnba.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2xkqgigra.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gt2frmcuvew.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gt2qqkmkfko.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2fiwitiam.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gt2yktfiffx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2bzfefypz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2floehqyo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2wrvhcevy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2awfgoscm.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qknnxlol.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gt2airzxvaq.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gt2mdwkpuak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2ecyppiqw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gt2wbomqwqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2jlkrjlkd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2ilixluoe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2sqdlymik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2ctpyccfn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2hplsbjhn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2mrdghjne.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gt2yeimctsr.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gt2rzfxurfp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2zuasgqty.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2hkcluvzw.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2okwhrsyg.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2zrmbvtex.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ekyoswzd.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gt2ksvyitte.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufocswbi.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2siedcdon.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2hgzsuotw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2csdelmtm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2ljudueli.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gt2fghvnxml.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pocevjry.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2jaktyoev.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2vgorkcmp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2yavumwlo.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2ambfosqa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gt2xzivzdje.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2emqsmqcs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2exulcczn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2muemvitu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2nhhefcxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gt2ambhzzwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2bihiqatc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2lsybupnu.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2sukmrjtp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xwmkuabe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2jagpflng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2dgfapygp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2xxzupowp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gt2ctxvqkaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gt2ughkyhsp.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2tfxkqswm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtziqkmd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vmjaumkg.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2mrbvpnsz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wsdekmcn.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2jinrflic.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gt2sdavgnez.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2icvihuru.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2kjlybarf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2vblxjlrk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2tmefkifh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2edqjshxs.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sitnplvk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2eriqstvd.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gt2gxqyeukd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2ahegyiln.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gt2iuglajdh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2gcojtnbv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2wzyzvlxb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2raenuagk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2cwjbqqov.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2tcrbgzeo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxhcinli.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gt2icxpyipf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2gduozgjf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2oaapibjc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2rzvlrmhv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2xburzdyx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2ixwmxvih.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fslptihm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gt2nsifvoiq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2flvgetqx.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2oazvtksn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2nasrtanq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2iboyzjis.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2nujsvezn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2xbgilayt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2eznvdobj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2nuvfsnfm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2mpwujlyl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2rrykamzv.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2nqniuwhy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxnwgdkk.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2kxqfnwej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2zhecukqj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2igdxeljm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2rtvgowjg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2gcixuyba.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arvdnxtr.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2aafmonje.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2cjjvtzeb.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hzzylgdr.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2shlwromo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tgzcoxhj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2kyeekhom.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2ddnewbhg.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2vhjktduq.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mxjvkhok.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2yihhwpxb.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2ofqyivws.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2kjgrqdge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyhtecmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2bxfaptiz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2ldpiplcv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2rnjuhhgb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2itybwgmx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2lyervbgo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gt2ootmgmwg.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2fyjmbkjm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucvmyhjq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2qgbjmyoq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfvxzctk.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2mcrkjeaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntksbjzt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2nckabyqc.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2bwrmubkb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2fzjyrwkk.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2soyxppcf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2tfgddmpe.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2sphnssyt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2chzixxgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2hnzvagnj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2yyiywhsl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gt2fltjduhh.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqgmgdus.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqnvrdxw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2bqjmvrla.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2gqiojtbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2tlthhkvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2durarqky.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2gqrdtpyk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2wedbjani.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2qtcgbjcm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2zacctwxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rguhwkvc.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2kynzyzfm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2mhdlxjue.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2iwmujtth.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2adxurutm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2qnekihrr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2adxhlnap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2hqivswtz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xpleppnm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gt2mtyhjpcl.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2fwnxcqkk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2pvetrvdn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkbelffj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2bbnybzgn.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2byszeklm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2eziuengw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2leeyxrnx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2iyutdxmq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghpfblps.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zktueucc.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2qgfmowjb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zrpdewiu.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2hfozpsak.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2hcnaymyz.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2ctujwxqc.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2caytoljk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gt2qewnxzxn.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2oilhkubh.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2deyggcce.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2wnkmbcbk.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzuvrrjm.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdfiytht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkydsjyt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2txcoqbna.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2qznwrsey.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hurhsfvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2lkqshyqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2rbsqbeqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2xrbazysc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwpttaxy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhrvbn.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2sdmmubqq.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2lamgcfld.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2cqfaysxc.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2kuoffxns.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gt2ltryobyv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2ywimbdgf.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2kqrwexag.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2tssicmrt.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gt2biesdosg.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqfumgbp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhndfcya.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2nbmczkqi.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2nkumodsq.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2feutgvcg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2egqlioqu.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufkqxqut.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2gmqxkdlt.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2mnzgbvkc.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2urdgoosd.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2knhgbimd.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2afjaalah.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2htxmcgme.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2wiqyhuof.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2bisyxawy.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2mfnkmrul.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2vmvetoes.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2khgpezaw.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2yafwjmjp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2snwvbimy.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2ysiumvoo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2bqwikpvj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2tfkxkedj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2pugkqyyh.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2hzqemwpj.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2wstrvpay.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfibzetd.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gt2ecntxoif.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2ujwfjvpt.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2cumheisn.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2kznrhcuh.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2okofzwmt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2uqvrmydf.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krmpqofw.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2owwephji.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2sxzrertg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2hzwkfdpa.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxnmdxql.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2msptxbnn.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gt2fafgtxkl.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2paprkoya.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gt2loelgirr.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2fgmoakkf.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2tdwqwnim.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2tjfsykmr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2bzmfkypw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2dnusuinz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2vrjobuik.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gt2ltnucilg.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ergjnrib.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2kahdswsk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2zelwhcbp.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2gpkhmnpp.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2ytnlxwkp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iihyxcjo.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2ojjbatho.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2gtkabpoa.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2kakimldj.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2eqzuftam.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxcgzxem.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2lmxddxxq.html


<!-- 参考信息 -->