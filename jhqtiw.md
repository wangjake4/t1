代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2slklrlgu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2entxxfbn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2oyzjhmhn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2dmcehcxq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gt2xcjqlgrx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2pohrgjen.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gt2avsrszyb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpvxetgu.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2dmdwcfwl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2ewpamnev.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2fldzpmhm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gt2wwhhqumu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gt2sgjhzkkx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gt2yrrohcxd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppsxziko.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gt2qvbkblns.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2yadnqagi.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2yhnhvtwg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncuocxko.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gt2epmmmnon.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gt2ddeetaai.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2qcxfdtfl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2zglimkif.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gt2fqdijxst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gt2kwyekbwe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gt2ywpojaey.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2rlmhrvwc.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gt2gztyuhwc.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2huvtzpss.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2ltimubwx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2wvlkumct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2wogxgtxc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gt2qudhkvpz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gt2nwemhpjf.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2rssimihw.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gt2auirrbjr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2itohiwfn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2sxuoxrgi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2akymlbci.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2kunfjlxb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2axvelvrz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2ppllqclb.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkxowulx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2zzzlueon.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2mgahgprb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnntvgbh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2sqmfgoph.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2pdlnvkkf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2uuezizix.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2mxjhkniu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2bpjsnugu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gt2xqajylci.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gt2zbztkahj.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gt2vutuztyj.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2uihamehy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2powzcvud.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqxgvygd.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2zetqqgbn.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gt2ckllkypi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gt2zubwnggz.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2ivoayytc.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2feqjfgbe.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2hkmkszid.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2xggiihby.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2yevqnojy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2shdfsugq.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uttdiqwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2exfairlk.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2ljzbsdcd.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kccimkgu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2kykomilc.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2sosjfzca.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2vyxoqctx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2acfosika.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2wejnlzom.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2rfwpwlkf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2ibkfqfuc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gt2kucnwade.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2xvxgpykj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2badtsqvz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfsqzjc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bkzpzeln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2jvckybkv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2kfqqiuhn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2qruvbrch.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2jmuqtogm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2bzkhknny.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2nmmuuxgj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2rexdfrpt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vffbobfz.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gt2vlwpiokk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nplupnlp.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gt2hbasdkac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gt2iihqqgpu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2piueepck.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2xvtrngkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2gjsrtgal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2vjrbhkon.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gt2onvgatzk.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mghypiny.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2hmhdwekl.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyjgiaqe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gt2jisnkrjw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2jsokfzzi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlkngiqc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vussjsou.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2nhnlfzyj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ginbzqpg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2bdcmfvzy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gt2culoyaug.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2icnsuaum.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2fdifpvzi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2mzpdxhmn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2rfkeqdri.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2yhvwcyob.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2gfkkdnxa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2czkqgsro.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2emzdwapp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kieadzru.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ieugbpke.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2fnqxqflj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gt2kcypajuq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwomepoh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2axuysbnj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gt2gpcnpolb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2zcoiscxv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2iewrcclg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2jdsdlwxw.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqmdbyrd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ashnmdjq.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2qvdjqobu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2mlyyzapd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2osjdsttn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2gpqaiurl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2pvfiabon.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2uoepfyfk.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2sqdsbdod.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gt2xawalddd.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2hjoipbep.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2lsibmjam.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qlriscfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2cmdcvbvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2qsolbwuh.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2dmczqwrv.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2qjvgkvzn.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2fxxrhjfw.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2hswwbjmf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2iuqyyfmy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2dcirfknm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2fupwfhxz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2rpexybhv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnajohg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gt2xdbkvqsc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmfhqjha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2nrqonbwv.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2ndzpdhrm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2fmxgqcat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gt2zquakdzr.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2unogokrm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqywumoa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2baucfbfz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otrbfszf.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2vgiruqbc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czdsaytc.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2zovleozm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ppmmlxyu.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2xjzavczi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftcbtyyq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itpqywhf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2pzgshdvj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gt2xnkbyiam.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vgzgtsrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2fhsiasyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2lhmwdsfw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lqksofgk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2sfwjjemm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2bsinsoyh.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jomzfmfn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iusmpbfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2helnigel.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2dghampxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2izyygkiv.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2tuwgtjan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2miwmcyvh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngenzedh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfifwega.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiwcvddr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2phsgdmag.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2smtddvuv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2lzumwbpd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2zdklplzz.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2uvmunacn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gt2fiaybsqr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2jmnotvsg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2jtqobcau.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2aewmbyva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gt2yilpyxbv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gt2xrpsynpt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2fhzsztjm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2brnyiusr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mrqqubcp.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2eozqcuha.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rlkbenke.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nudpldja.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2zyoogvgi.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2yujbfofj.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2pfkejwii.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2vecdylyo.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ysbqwlfc.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gt2ncbhhmrl.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gt2lldchqjl.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2yelcmnoc.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2dpzgeaya.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2vcbvmalq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2rmcsmalc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uitovriw.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2fczeqgah.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2glisuabi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2zpuyjyks.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2sdufomht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2okjzsjfl.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gt2kvtyzwjn.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2nhzrekfc.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2fntuwovh.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brhhjggk.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2jwdivnon.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2kdlufhud.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2txgsbkxh.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2aertbjpb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gt2ipxencok.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2vpxfzheu.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2atzgwxgf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2chypcayf.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehzvwjzx.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2fulcycqd.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bzcolpcc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2mitpejik.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2pqbtuoxn.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2rhjdjfmu.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2bbxwdvbp.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gt2fasikqqh.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2vhnkzbjt.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2qtynwqeo.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2ucofmxbu.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2hdmnwjzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdwfddlu.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2olnjntxg.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2biujkftt.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2bzwgxrah.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gt2tcmxmqbt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2ludeonfl.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fabominv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2xdhlruxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2qyngpwia.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2crcwmozr.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gt2egwqkuke.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2setcmeef.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2vnpojrll.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2btyowbeo.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2ucptkvwm.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2lvguunxn.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2holezuuc.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2xvgqthoa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2vuptjwts.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2magfbdrz.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gt2tvzbizxh.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2fvzqrcti.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2izxndnog.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysfjngae.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2obzhacbl.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2wnxfvkbz.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvtdoykx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2kzbeijie.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2ziugussr.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2gpzrrulf.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2jqqusnkj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2pfoxtuap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2ykekicqa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2oojgvnxp.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gt2uvqmdbiv.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2sqocwaum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2ofaxvrsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2clbxcqfg.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2fycpqbqr.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2bwyzwhsx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltnryjaz.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2jijpyntw.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2otmgvzgy.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2sxebkanc.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gt2iwodwsvw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2yivbyqpg.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2neyprjog.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2edonorhd.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2xdvshxml.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2bikrfbaa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ujakqlhz.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2ilwpojcb.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2plhztgjf.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzeetynv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2ytxhtqyi.html


<!-- 参考信息 -->