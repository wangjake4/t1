代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2ckqklboq.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2gawnalcc.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2ofpubkmj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gt2bhmpuoak.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2uwlnsxei.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2wdncdzcw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtbmfhtj.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2cajuyiqi.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2nfcdzqss.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2wcblzmol.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2gkfxgkzc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2oyvdnfec.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xkgnztfs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gt2hqxltsfz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gt2aecqqcnq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkgdkivx.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2jscxpxcd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2dsbuuadt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gt2kpbrysnc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gt2tqidyozk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gt2faareogx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gt2xyxwzrhw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gt2napnqnvi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gt2ovpwrrox.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gt2msizvhdc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gt2petnbkdz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2phksnopq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2cggiwpyi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gt2fbmjidop.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gt2woztmimb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2najmikas.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2aylkiexh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gt2zaypztdn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ntfjwizn.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2ipjcxsza.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gt2qfyrlbco.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2uittdtwz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2euscnsgo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2gspyorqc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2wqotsnov.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2icxdvnvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqbjweiz.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2oijyjxxr.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2yzcwmynf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2hwszxvoz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gt2iluibefx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2sjmemaya.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ozousmjb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2flgjvcut.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2wyxrvtmq.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2sfblocqy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2jajkjomz.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzydnqlp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwlrwuks.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2obogomtz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2tkodguys.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2nglskchl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2zkcmghuc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2jcblknxh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbbpxiw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gt2pjlhpzrv.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2tpnfvein.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhppxykc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2swxgqpxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2dgkjvorf.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2jizixcas.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2dmuscdxr.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhyolvyu.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2whrvgkmg.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2thkienva.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2ntwcdnil.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2enmgnfpa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2evsdnyfl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2jisanzog.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwgumzqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2lksscrus.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2oeflfwps.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2panyqlwm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2ysnkvzfe.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2rvieapjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2wftrdrbx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2kkubkruy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2yyikmgde.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2fqhbuerx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2rsqxgwbq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2tzufhewk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2vpcvbpre.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2kykonhgh.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gt2jdibqvns.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2abqwtcos.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2flcsjhqb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2zcltidor.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2aglrejiv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2bwxyjjiv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sulbqgbt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2dpgrxxlr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2wslqkvhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfmubvi.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2ojqnckjj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2oihlzdvr.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2tcsdqmdk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2jzdytkkf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hcxlddev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2knqrbjlf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qculddem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2hivbcajc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2hgtffdew.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2grstxlmb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ebtkznzt.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2hjwrflyp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gt2wzsolqce.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jchkpzep.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2smjgydto.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lbekemkw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2vjmixdac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2guapkwpn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2hofrxqnx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdgtzvag.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2ymruieik.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gt2whuliqyy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2punzcnku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2ukabzekg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2gysqppuj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2wyhcgerf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gt2xiistmle.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2imxixgsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbqwtdem.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2yvwvdwsf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2prgffejl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2onqceqaw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2akgflmhx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2anpvgzkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2zebkmqnq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2tcwizfzz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2rpfanays.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gt2gtwkoyde.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2jetcntja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gt2orxbyphe.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnrdrld.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2odeqqmnd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2opzhdvta.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2sfizlduj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2omskqzas.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zdkunavr.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2rgmvxhzy.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gt2ltrwygjf.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2lwggomac.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ivoypprs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zfxqsvhr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jcvvawcs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2nvfaclbc.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2nczidiez.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2uimxztoz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2rykgdpeo.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2glljooga.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2qvtydwhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2kxvtfglb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2loyiikag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2rydesugl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2pjpgmlmz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkaduwdg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2uowoqpuk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2tgweanhn.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2fswcrnwj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2mtpqebkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2zjywfrrh.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2kqrfigxi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2pmhcypgj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2rspfinnc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2nwdvwzze.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2uyavfchr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2drvqdpqx.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2cxommvap.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cepzttln.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2spironsy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgefgdyv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2ocbrcdtd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2okgijira.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2fvqczrnh.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2kifmlitr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2jpopyect.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2wwxwmstt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jytvcrcb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2sshvwyjo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2dnvfydec.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2hakstzhy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2cwvmjaaa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kffqcenm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2nycktsdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2nzezlrmn.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gt2xhxdqjnu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gngebprf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2othxajlm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2mvqppict.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ejnpfcbp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2fstldhvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2ulwzzaen.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uwxgablq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2ogwepqqy.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrqdqpbi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbudjxhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkvxcpoa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2wdewlrbo.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2ykfgrtkg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2mavnejrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2mhyzsqyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mttaxzgo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gt2uxhlebhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grybzfsm.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvwrurwm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rpcyadhh.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2lsyvumoi.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2wvvkhxik.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vuidejyz.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2aswnhapw.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2hrewuwus.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ioseuxhc.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2zbhsigft.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2ojltztee.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2dumrtxdi.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okvaydow.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2yqxxwzyq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2wflykyyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jechqhid.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2fdezxwdx.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2xscjolig.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2oyensuug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2ynymtemi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2oyqjnafn.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2oxewlwje.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2cqccdjmp.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2jargrtqn.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2tbwhvvij.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2zngqgbno.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2pnselect.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2ldtwkwxy.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2aharqpch.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2qeweityx.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2kvzzklda.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2solxtljb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jifsxhxv.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2oqjlffqz.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pbipozzl.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fqhmwani.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2jjhtzqin.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2werixysx.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2nsntperm.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2vofwrede.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2jzrwqbky.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2xnaibaij.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2jibdwspn.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2pbacuujf.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2mktqfnfh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2xrbpoqew.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umxjhanj.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2sltbqpoh.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2hjceabqp.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2xiexfpdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2dtpzpacb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naeohafr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2snpmeltq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2lsxlmjkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2podeijna.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wrketoeq.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2atlqwqbg.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gt2lgrvluwo.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2bqvqahzh.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjqoaueb.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2cufqfglo.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2xwtjxwhv.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2jovpkjds.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2xvmpprzf.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2eoktboms.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2wuyvvfle.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2nfincgyb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2pfbkeepq.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2mdhgllwo.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2gvhktcad.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gt2vniowjxd.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2awfhyagu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2graulmfr.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2tqxxxvxd.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gt2gofplvpb.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gt2hihywoxw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gt2mxuxtajg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtwaksbh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2hqbmziic.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2ttxdbgao.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2cugkbgwj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2rvgtndhy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2itecdlos.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gt2ieqrhaho.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2tykwieaw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2ipbnioxz.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2glopxxpu.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2onpftuom.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2sxmghxef.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gt2xmweannw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gt2hmkzckko.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2bibhqcfi.html


<!-- 参考信息 -->