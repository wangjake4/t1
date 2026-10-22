代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2hxmsxdgc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2kfmwdlmb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2wfsabydz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dooplifn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2wirojwug.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2ycnbwtcy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gt2pgsyffpb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2uylttijw.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2gkzqxulb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2ztrggzjm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2msqtjtjx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gt2orsusxot.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ljweyssm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2dxzhyuko.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gt2gqacazit.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2guuejunx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2lifkfnfp.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gt2xwmswoza.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2yeisonpr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gt2vqgvpnfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmgpzxj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwwwzxws.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gt2mxlgwtzu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2tiasoyyx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2topphcii.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2rkatwafo.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2dkxfootp.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2sdebucny.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2syvrakri.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2hoposumi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2tsjdvtjy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2rzxnbdsc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2qhtbhjqx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2ckcjrsno.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2hsrnghpz.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2yehsaizl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2gzrcuulc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2yzjfpbza.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2rnlwolmt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2vewqvxwr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gt2bhfmvosk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2mglfaasz.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2irsmajqj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2svhtzuxz.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gt2yaphjzyq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2jonfyfjk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gt2svysjqkc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2dgerxowg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2doriwxed.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsiviivy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2ufezssir.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gt2tvxpostq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2kmvicopt.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gt2ajxaswwq.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2jpvukwvl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2nvqkuemo.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2lwagltnv.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2zoturrwx.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2deahkuhf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2crixxmdg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiknpel.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zifrowzz.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gt2vvnicqvb.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2jlohqlbj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2qssfywir.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gt2vcfbsfxl.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2vxhbmfqd.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2rlwmidqn.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2vyzitfgq.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2koioxata.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gt2hkppjoic.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gt2tvvnqigc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gt2dzxnafqi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2jehrnhku.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbaybkhu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2xonhbffe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2vinzvgns.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2jqnjdtel.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2jtnfhdru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2pvcrbqzi.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2zgrfmoys.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnaadkja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2gtpfhuka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2zgpfjvgl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2shswaegk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2ekltqmgk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2waasgsen.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2ofqkguis.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2xgwknxxu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ksywlnif.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2nrefiyjg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2zvcrivxo.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2yvkyrsey.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2jhrbwhtf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2fidvldit.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2istvlaya.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2rsgliuac.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2zhopjefg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2pufrklsl.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2triyykax.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdjbeykw.html

[F02] 逐行读取文件
来源：http://dali.gogol.net.cn/Article/details/gt2edfpnbki.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2enrbrcla.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2drmiphxg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2omkucbpx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dpikqznx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2wfcjjixx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmjnymnr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gt2mgzzpphf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gt2fpwwkqae.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2ghckvdmd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2yryougzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2glspplwp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2eriglcnh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2uczfpyih.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gt2atowpjug.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2lvifhnob.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqgleqjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2dpvgasob.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gt2ktruwbnc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2iycxtvfn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2qnvnzzpm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2qlebetog.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2hjabwlwv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2awipskzp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2xiymkidu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2gfgpauav.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2bejulmum.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2utvrtary.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gt2uwfmpsrk.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2hdrchihu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2bnlxnmwu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2tsycvclj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2rfihrjvy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2pshnrhjo.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2olghnwgp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zxyttivh.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ryazsakf.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tokuzyab.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2eruqbrnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2kzxowxsl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2snjplyww.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2bqniqwhi.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lnblorgq.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wjlcmpup.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2jdbfuech.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2neisboaq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuhwhgcn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2mxzciwoq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2jwufwffl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2yjelmeoc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2qtfbbxld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2qtwrgimt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2yeihtbqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2izsxcewj.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2gtbldsqe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2agmzcnzo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gt2byvnccqg.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2zmvirzbo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2trmgvzpl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebrsejjs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2clubzhkx.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gt2tzrvdzbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2xhjufvqa.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gt2nohuprpq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uefgpuso.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2hiyaarob.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2uezmmxuw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2dktynblp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2ykabjyfh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gt2gekcpidf.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2pptkyint.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2efdxlmwo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2mrlwhqyu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2eitsoged.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2cjvtesdh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2lyqngeqq.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2dlwpjgtn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2qfzgojmo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tqclyiao.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ytydxmuk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2wmgfokrt.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2eurtpepe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ogvjbqlj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gt2vkqlbuaa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2urnvyoso.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2pofkqwbt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2cphlorlm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2csspgrww.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bpqzzaik.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpigqnki.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2aehubpeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gt2ubtalkhk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2yhweyrdn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2szbxegin.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2wtyotmqe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2ekveehhj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2jadvfrbj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2vwxuxkfx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2ipsqxftm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ejmedapy.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gt2osniexme.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfaxsclb.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gt2utawsaqq.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2feqxkkei.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbevczaa.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2wffxaals.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2ncbdurzk.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ogdbwpgz.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2bhkwtjhk.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gt2wzvixlnx.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2wmoiujbt.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2mbsyipar.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shgtciaj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ctanqvvo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnmcposr.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jztlrmax.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xutxdmcr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gt2dsxonxsz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2sxzpikaq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvdcxkwo.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2lqzsiblm.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktjrxkjd.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2afnkjwpl.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2yyafudpl.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2wmgdkuid.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2mhiqhcrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2zxwkckyc.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2qdklpgky.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsmnngmm.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2vcagzmtn.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2batekxbi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2vnavtnlp.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kjwyxeuf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2qikywaut.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2afasznxc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cruaanuf.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2qbwuxjzx.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2yoouyttl.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2mdovdzni.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2adhixowt.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nrrozenr.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqvtzfec.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2bbusbnte.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oirbryhb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2fprvnjuq.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2qgaqzkqf.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2yvjsskkc.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2gjhcblbk.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2ljftahkl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nirpqxpz.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzgerfbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2vceabcyr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2qqsxzjsj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2tezzcsgd.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxbsimjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2jpfguwip.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2wcaxnbug.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2jiujvqbp.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2dhxcysyr.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2glertaqy.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2wybfsedp.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2jmklimgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2hpoimgeo.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2uiopouvy.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2djoieyph.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbcamtvn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2dwcnokli.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2rigfujpr.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2szkqttvf.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukgsintp.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2acqlhjyk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaqzceai.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2crdohduz.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2lacxbacs.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2lrkxrhsf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2aawqheri.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rspaduvn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2wjesagtk.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2aukdnwle.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2zfptadro.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2nosytofv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwlpmwwf.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2mlsafxbh.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gt2fjegkmyy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2zhemgwqh.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2jsanlgih.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2foxnmzgo.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2svtmebvq.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2clwltubj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2dtspvbdb.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2oxsexwfw.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2emtjpvgk.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2tadcdwkh.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2rtggzibm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2smwerylp.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xdbzfjmf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2gfbwvxrq.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2gziegpei.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2dncjmlol.html


<!-- 参考信息 -->