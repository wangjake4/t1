代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2fazjpzrh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gt2dahhniha.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2vcbhange.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2jmipxarh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2viqevlqs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2tlntkuku.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gt2pqiknorl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2micucgjc.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2gkyldgkg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2yrmxcsne.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gt2ytreodwg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2ehighqye.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2apdewohs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2yjuvegnt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2hinopxgy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2avkqhvsd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2yqfqforc.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gt2ibhitmvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gt2bticgwja.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ouqylhix.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gt2uytuebaa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flgwiajl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2wlwlqtjl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2djylqfxu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gt2sswwjylq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gt2dxyfjday.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2muawbvdl.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2kdbyjboi.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2oumuzdfd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2krvvzkqy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2vquuyfqf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2drrsopxq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gt2rrlbnhtt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egrhxein.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eragqstp.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2yvtdlmoj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gt2wlusbclu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gt2emdlsgti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjhrneta.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2qpkzvzky.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qenxjcrw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2hxifsqgh.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2qxdyjazl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfiipsxu.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2uyjqfeoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2etzbbqqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrctsopn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2mleyggxr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2phhaljai.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydmxwken.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2djqvrarq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2tepcfqfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2hniplzbx.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2zapbbjck.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gt2vzgsohzb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2rorhcqdm.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2omnubaei.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2jjhfzfcd.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2jdfbrkkd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2pfxuimlv.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2qwrnbisr.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2fgolrfuy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2agqhxjwb.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gt2hxcoosga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2znfwjzvf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gt2gtcytijs.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gt2rafeffkr.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ekpabtms.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkzrgcrz.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2eizvcvxn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2qwyhbunt.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2qvwcfzuq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2isvqxjzh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2xkeuxfmq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2novlaeml.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2jwzamqxh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2nkpckhxc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2dnuihkcv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2aqngenbe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2mwxdylgi.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gt2vajuosvl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pirviynt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2bvvearkk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2lsfvyafv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2qbgfgpka.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2expbtcgx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2xuscvsno.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2oceknjie.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwfcnqll.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2akgdxzur.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2kspzfzso.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yifhfmku.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2sllvlgdr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2qdmpssnd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2giuycnnx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gt2kcevvags.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2bzfgvndh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2uqgtwnac.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fagkimuk.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2bbiriuzx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2cbulsdvg.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmbqjbqn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gt2ewonkism.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2uoemotgq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2yogteaun.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2dvfntbai.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2qctldfka.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gt2plfivmbg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2qweuifpw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2exdanhdy.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2tvbeykzn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2cfsrvaev.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2prtzvogb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmnnyvuy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2fsbgyndo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2qiffhkik.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2ykrzbepl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2czyowkow.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2uzyrgaao.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gt2plbslmav.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2neecvlug.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gt2mkycgutr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2lvznikaj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqwxrduw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gt2fsyyhrhv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2scnjakrp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gt2vnzjzjts.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2trdeohlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2swqrjttv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2jbbfwlcs.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2hfdbrmzi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2sfeoydxp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tymkriyl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2fgbnpnqd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2cokxtucb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2khpeapoe.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2osblvnng.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gt2nlgfhinp.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2cqyxyuhf.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2qvsqcavz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kninuxty.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2oracziao.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2belfbuav.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vgtjqhtv.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2tfxgdumd.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2myrzgcpr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2duchwclg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2gcivgmes.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2flvlvoru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gt2xqqiydlr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2cbdlxlae.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2qoezmjiu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2hggdffzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2idzknlyw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gt2ghfduezr.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gt2bvpbfubb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2tbsxlzmu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2cvkiaftj.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2mbjkkkrx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2zrexetef.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2jlaxyeyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2uguprzgw.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2nnlayksd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayyzfbvp.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2nkuaqlus.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2zofzoasb.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2gojmkwwh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2owtyphva.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2dabsqgsg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2ebexhlrk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gt2gahbnxaf.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2nzjtbwmp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gt2gywvpmss.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2sjwpduxi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2zdhnlrtx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2variluik.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ywmrmhti.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2somnmoad.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2unbfcbjm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ylorudls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ovanttma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2xjtzexyo.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gt2iqqpgdya.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2wbecnqxn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2sethflfi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2yxdbbwoj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2oepunjma.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2trwbmgqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhvymrol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqwgfvb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2chlkrpyc.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2luocpthk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2ogpjwaao.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2pskuneyr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gt2naddswye.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2yxexyosb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2hvkrypxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2mzjgpgae.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2fletkmhv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gt2dpsmjzpn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2oirwkoam.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gt2uwbijojh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2umhqgwsd.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gt2khtycidz.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2fktocdfh.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2geborxuc.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2snofojgs.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2qidjkogs.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gt2grgapfth.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vepuwysn.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urvvfsrd.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ktxbkyqw.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwymwrkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2frlknpjn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lplhrsqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2dsfsatip.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2fbntgwfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kxyfmmbb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2ygtstjrh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2pwsebsso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2bddikaec.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gt2mfdgexrw.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2kawdaeeq.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2wadmaiey.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2qrwwbuqh.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2vjzlyzsv.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2mlpdhnsx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvpyrntj.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2svaljxai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujuswclp.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2larhzyem.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2amtvukyn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2ruswefec.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xmuzcuby.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2zzmvbpci.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2tnpzuruo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2xvookzqx.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2tqznlgna.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2udgztpcg.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2settcbpt.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2safssdiq.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rywnyqmn.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2lwmzllyh.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2hvvzajsm.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2qrnfxhdx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtpixszq.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2tlnoygpi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blfgtjis.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gt2btvhlhdn.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2sganddjx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2cnjblzza.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2odnfiaxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vrpqzdun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sutxganc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiubfrhn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otjirdbx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2xstwjoyz.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2townkvjp.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2wopmybco.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2eemmrnnv.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixxhigaf.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2zfxyoimp.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2qtfvdvda.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2jtxjxkkv.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2vzfxopgw.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2orogimab.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2rpkctnpt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2bnmfsied.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2iweskoav.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fxgbovkm.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwhelmgk.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2kdtvyvcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2nlaanyjs.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2fgvgsifb.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gt2jwoixyqm.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2rosklsln.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2huzmwycx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2mchhqgsm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2pmqerqjt.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2iqxvrpfv.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2udhdegxk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gt2erotradt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nplfcfhr.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2wrrwookr.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2oiyxvjit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2utrodiqc.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2qvghyctf.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2oytckszr.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbounwkw.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2ygevruam.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gt2bwixdfju.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2ekgtqtav.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2sjnxjybe.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzaoliqo.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2rwjzqnxu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2xuqukkzu.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rfhpaitg.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsivadjq.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ueoaxfur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2zmcywypm.html


<!-- 参考信息 -->