代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2fhydfrrq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gt2vlhjcwsc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2kvfcuwtz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2ibaijohb.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2hepoeqje.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2ljbvkuvt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2ixdujlky.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2iaxfmuzf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2wszpdxoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2ebydqbcw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gt2outikwnj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gt2aysaakeh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2jqxpfjmv.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gt2iizqqlpd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xlxfrxkj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gt2lvixsgfa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gt2yubrksht.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gt2hubxssnh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gt2kvoctbrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqpahide.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2yffklocp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2emheimxm.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2oggmtgtq.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2abnfqblt.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gt2rbhvajvq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2aenjhgrm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bslzxist.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2bbytmpou.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2jusszurb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2klcjmpng.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gt2zqavkpqx.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2jjxvwwnt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2ugpiujax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwrwnoyk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2bwztkgua.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ilzhoucc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gfwalvia.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2wnpncfna.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2xzocsvim.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2obawfgrq.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2gwvemyul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gt2znvlapbs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2exqommwt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2kkhhzhmd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2nheoehfk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2vngjisva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2tuzkfgvx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2onnekhlj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2itwdzhfh.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2riofiinc.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gt2iexmrmuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2mackcjju.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2dyiozrpd.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2egwwjnrn.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ldvtidzx.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2dwzdnjjm.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2flykemzy.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2wyxnhwkr.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gt2mxwhmien.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2rlcdgert.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avqlwruk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zmzkdjab.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2lglwxxdb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2snifdnqg.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gt2ofjgscyj.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gt2wzaxtfhu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2upvlejnv.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2lsavuazk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2mupguqwl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2gkersank.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2nmtmjvky.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2qqgytwbw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2glooqzwk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2suvpwske.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2tzeosows.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2caldfxqx.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2wokzwbqh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gt2qscjsfln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2snoqcxcr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2vevojmll.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2paftqvmk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwuzel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2kqtgwedz.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2mxygycnf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2flbvurkp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2dsxeqgtb.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gt2orjptlgc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2iueoekrw.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2shrclgyy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gt2crspbfxx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2vvrfcnwi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2rctdlbdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2fajlxbxe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2kvvlrecw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gt2bwbvxqlh.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2mhrimrdw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgiheugh.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2qxxyzfry.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gt2oikwiyrb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2uppbjvai.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ycehwldz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2vvqhranf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmhhtxe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gt2iitzgzjg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2kpucrqzv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2cizahzew.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2zxshpvro.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2chclwlmj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2zjdlkqpw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2ubdnolsz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omiuacqy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2fkekxjro.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2zkqocnvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gt2rbzyyaly.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2gefwldig.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gt2kboypfwc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2rkhufcgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2wpbrzffu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2eeywfsdp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2cxfzziom.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gt2gpnzfjhu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtvrfwyb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2tljbmcyj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gt2utfrfkru.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2aalgeyze.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2qhhwnger.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ixkibiwe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2arjfhfyp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2txptshim.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2rmxcqavr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gt2dynmcrvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rokpbugz.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hdefmxac.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2dzrauixn.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewwpugjn.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2vvxdahyx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2flimuakb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2msmlaybv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2kkhtieuo.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2exbqmakn.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2funrxuxn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2hadlygal.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gt2byhnsulf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2hgfeisuo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2oexjrsuv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ztsscnfv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2cyvvuouf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2vvmqtxgn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gt2rrxqmsdu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gt2njgkgrbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gt2tjxkfhzy.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gt2ksmbibkw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgcqrxfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gt2tpgbcajs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjlxdta.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2yiaodble.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfiizbvn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2qjfpsvgg.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2zolnfiqq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2rdkhbhyu.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2rwswfgrw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vudwblhc.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2rhesdwpn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2quxfjrdv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2syvciios.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2klklonsh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2vyvudbli.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2kxiojgve.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gt2siqaqmyl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2jshuebwi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozfrcuzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2fobmjxis.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2hgrayuqb.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezcfdldv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2njkuhqlw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2qmzdcznh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2rcenkibx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xtcgffjq.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2soulgrcw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tbriromd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2nxkhpozt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjoxhdjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mfxsnzon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2bkubylnk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gt2emggvcob.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2qmxdyses.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2caeforfk.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2tpqspnzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yppcdtfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2ogqsscbm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2rcrhzjab.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2dmlhnbah.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2wcswmshd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gt2slpecfsx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2kyysoxli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2rahqdmrd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fgcafnvn.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2bgjpvwgp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cztnkfwf.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2gkuzgfrx.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2lfglpbhg.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2fwtsrajp.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2lsgccuus.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2pgvzhgbf.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2hsxnyxit.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2sqmgjzlq.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2xkimhvtt.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ziiopxgu.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2cafvhavy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gt2ruafcoaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gt2yxaajkjp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2hrizfwoz.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2elrsnkbn.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nudlrdyw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gt2ndjocyza.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2kddulgyr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ejrzwede.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2bqligamw.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2fhwpgqrk.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2cwuqkolr.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2akocgvnl.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2pzbuzsmd.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2ijximwdk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbawrhzy.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lczfcisy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2frbdxref.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2aggnadyt.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skxdtfdl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pidlcfpq.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2eshvbgqh.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ycyzmtpm.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2xczibhzj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xveftrpp.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2pymqzpyd.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2acinpieo.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gt2gbehiwix.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gt2rbdifknh.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2uphbmgji.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2zizhdtql.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2kronmzxb.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2izxvwfcp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2ebybusln.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gt2vfpzywby.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gt2pvyinyoi.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2ztpjzhdy.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcakxeoc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndewqvww.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2redieeml.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2agggikiv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2bysjvqhc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2kiabtfxt.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2tnwvcczn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2nluyvpeo.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2utzrpkvk.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2czpbnpmm.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gt2niwvwuuq.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmuvdlhm.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhtxzkbl.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2hfufusdt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2dqypvdne.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2gncssdpi.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2jsnirbyy.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2bnovsxkm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2upeddtib.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gt2rtnavmnj.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2krcntbgf.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2hqhifcui.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2zxxvqtla.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gt2gyldjiec.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2vrzwrarv.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2elibqjyk.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2toyckjor.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2uulkxtab.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2anjyeuzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdpstduv.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2ojgjmknc.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2llnaqekk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwawgxsj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2ntaekffg.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2abginqva.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2glohwlsa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gt2yuaokzfd.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2vtuosmmk.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2kddvwpax.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdcffklf.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2oelatztz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2aujwgabe.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2odupynol.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gt2zrgevbea.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2toyqfjvx.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhpqcapn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2fwlkidfe.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wqgebzhu.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wawdkzoy.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2iftitnqx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2rmxegeox.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2abshieni.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gt2vkcgercp.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2gnixsqfw.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2xqqpbfhe.html


<!-- 参考信息 -->