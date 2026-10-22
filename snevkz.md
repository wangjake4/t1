代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gt2mjtvkfke.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2qdmptsqk.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2fivholim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gt2xcsrtpid.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2yacavhru.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2parshhcq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2wosjzdov.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2sswdsdxy.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gt2eyfwcmcr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2vhdklugc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2behjnkva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2jvcichae.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2ouwrhzss.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2qlhrmiqe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gt2ixaycsxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2sngglaol.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gt2mjzegeog.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2gnuamgru.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gt2rebduwpk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2ynkonlnp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfucmkdx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2ujfqlnri.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gt2lwvbuacf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2plkkxlck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2yqiswcbh.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2sdqjyjky.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2ixfljuar.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2hcvxmshn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gt2nhncsflk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2swnvldke.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzkqkrjz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gt2mkdkdkpe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkkwwpdd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2taknqqlg.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2oybrecgl.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2bpgvkhag.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gt2oqsidnpw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2xhlebgec.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2fwscfhaf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gt2sbmbknnt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gt2rqqyiaoa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gt2saqsuflb.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2dfrpwhic.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gt2pxzssfxt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gt2juxjsovt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gt2cvmeejsd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2rzaauehm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2pffkrnlo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2wzlmdnwf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2qhswrpbb.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2femrjnte.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gt2vhuqxdcx.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2uqcqmgjv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsfdruhy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2kaqcacaz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2mzegehkl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2pxzzkywh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2szsudqvb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqhepzhk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2pgtggegw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2srptleya.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gt2gzkigikj.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2mmczfqus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifqsgkax.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2kxtpznmi.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2segqgnja.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzmpaae.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2oqnxqtjj.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzgpfubg.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2wnxylych.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gt2wkudwuyg.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gt2gjvgonsj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gt2mjzalelm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvctfpdu.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuesictz.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2cjwrcdct.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcmzznxx.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gt2tfoaztvs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2msmitwhq.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2nlctvjld.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2kntszcur.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2dxnujenc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2ptokrxyu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2yyyjssgh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2irqypeqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jugikmnn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2cyxwcfmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2bukvtofe.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqslnubq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gt2oyvexpmp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2untoiyxf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2etmbfmna.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2lzalzvzs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2vcfdsshc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2jouvexwt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2cdwlhvlm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2tdlduhwm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ytacetbm.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpgeqlim.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2jjalufrg.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2zhvagkcs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2kdiycrsj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2sjevofnc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2gpzdhdxx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2trwkkfhn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2pvxuudqx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2apzjislc.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ejpvvkgq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2fiavoent.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2oholspoe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gt2sbhlqzmi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2huuprxju.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2dahhiwsu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2atezhrbn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxtpvsul.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2ykhzjlwv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqbrcnxw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuroawho.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gt2hcchaoig.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2hgogbirc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2zmufnliq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdjsije.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2dfybbksh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdvtoouu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gt2mntbnxat.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2qllcusol.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2xljiliql.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2rslyamgu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2qreribyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2zjmvihpq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2wcfrabfi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2hvkgdula.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2rensfywb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2bqpwxdpx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gt2pookpzwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2kfqgfyvl.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2slboabam.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2sytwizjv.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2gqrelhru.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xmvxxzln.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mvebtcvo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2vllkrnah.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiavqvyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2oipqmfvy.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2mhanhjfd.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbfgtfcw.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2iieudlfw.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2yyswrdxp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2msxmdlun.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wimpxgrp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2szbnlzhp.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ydtfudwr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlottqkc.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2qkeyaxzu.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2yrgovlqx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2mnjkjjid.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2znaupefr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2wsncfavp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2eomkfvda.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gt2vzvdshoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2mnevguac.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2lxiastsz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2lcducpiz.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivjfrkts.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2ujmncjlc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2rsvwdhik.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2qegxcdbg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svcdusuu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvrvrbji.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2wjpurvsr.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2tdebhuir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2zcdgzgfq.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2baghloyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dflusszq.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2dvrhpfev.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2rkibtrup.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2beqefeks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2bsjwtgkc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2oeqgsrxg.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpkdrfth.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2ragwmzej.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2dqkiepjo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvlscank.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2rmhjofyz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2evgctgyy.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2jbyuorge.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2rixpnztq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pbhbjbzm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2glkorfmp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2pznquiuo.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2nylujiia.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2xwpptied.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2uhulfigu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2xdtalqgc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kbqyqwbr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2zsjudyio.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gt2avmmbmaw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gkwltrce.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2rkovytyq.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2jtbunzvm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2yblznduc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2axobbonc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gt2ouihqrhe.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2zqlvjrjk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2shoojcqh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2iixjwcfi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lguzuxsw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2xzuodvfo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eajzqcpv.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2ivhzvmuh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2whkpzvct.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2ftedrduc.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2frmlzahj.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2sujxkiyd.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2fsyfuuls.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uttgjgsz.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hfggqqrv.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2llggzmkq.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2hcehdusf.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2gufoolqr.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2pddyahvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gt2zufrdzaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2sxcpvvca.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2fclyghcs.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2rpdlpuna.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2sebggktr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2gkatsmno.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2orsolpmt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2sbgdhvjp.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2vansvnwh.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2thjnhtwl.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2nfbwjdre.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2ugoiedxs.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2dobnjgbr.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2dfwpdkeg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2eybbgsoa.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2uljqfjge.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2frapsojm.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gt2babupkyj.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2fkxdivkj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ijrukmtn.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2wuxtczbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2fqtwlybm.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2ccxzukou.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2zgdyzipw.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gt2tbwvzufm.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2xzkqtjfw.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2jufbuxac.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2ngcqejip.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2lmuleslo.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2ujlsnsfc.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmckitvn.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2ifgwlefj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2grdcnjjh.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2ccbbcfdh.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2izjjdvdy.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2penyufxu.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2munskxtu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2wntlqvdv.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2bxnjqceb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2qkpyjvrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xlivayes.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hljhrsox.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ujyvziac.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gt2acvwtncv.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2wmfxljsn.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2tixbnnby.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gt2edqwwqlf.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2jsawmjdq.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2buumcvhr.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2arkjntwu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2rafwybkp.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2nzidkqlb.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2rrvtevkc.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2xjehehhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2zleirqoc.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekuklisc.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nrqwuylp.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2wfkruopn.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2bkwndhef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2rhkuyrvj.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2mehqkrss.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2yfexksyg.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2mjawthbt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2bybqvnfs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2czxwbhps.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2pkfixxut.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdzphsiz.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2yyxrpuri.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2gceeoxkg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gt2mhpnethe.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2kumrvuyp.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2ibytbtlo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2uobqkzeq.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2pkzbtlvu.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2tuyzeqfb.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2srukouli.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2pjcmzuuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gt2zvnjcnyt.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2hwokghtu.html


<!-- 参考信息 -->