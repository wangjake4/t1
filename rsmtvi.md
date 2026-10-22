代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2wohiucro.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gllyunwq.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gt2uoobwspx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2sbvutgjm.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gt2hfjhvkck.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2ixdgvuib.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2botpmajd.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2ulzckync.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmtlnxwe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2prpjcpfj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2avabezpn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2wfwohsou.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydyrfbin.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2wagwvouw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gt2cinjjbjj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2mmxkxjgo.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gt2cfvmicgz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gt2lpssnbzm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2irfyatjz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkycuqnt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gt2vfelpgiv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2ymgwathi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2wktswrwo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2befdeebs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wevfkglg.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfbogxnt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2jpuzyssk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gt2zuokrysw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkldhkpg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gt2wqqdmbys.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2njmefrxe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gt2qgfgkwrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gt2zkssewwn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gt2rmsollgg.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2fahcmpck.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2htwnokge.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gt2jcxluwwh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwauzcca.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2taiazxoy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2hkknzhfv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2keijlrzh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gt2crnbiyfj.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2usoknnhr.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2uxkdlaoy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2lwdfihek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2zxrvzzos.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2ouglbdye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2jthfzlgh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbyuthbg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnmskuba.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gt2fuyfsxcm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2iqiehhav.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gt2sxcnjdwh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gt2yeqlegjq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2erbscjoj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2kjmkceqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2gdmkaeyv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2axkjdejy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2wphtezqb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2blgrfksb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2hekdtolr.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gt2ipjcpnfq.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykafchcd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2fbynqtuv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2vrjacnrg.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2gysrgqjt.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2hmlpejpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2kehbziuy.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gt2ocsuuenx.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jddrqsoz.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2coayafwa.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2dfwwembt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2ayqvjxbn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2mpxrdlmu.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uetozjbp.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2wscuqicj.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ekenvmfu.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gt2goyroogm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vajtlmil.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2edzmzdvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2nyglxjcz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ezcqkzlv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2shrxfkdi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhnslqon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2zaogknbt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2jtqpofdl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2zcgenkbs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2vlhyrdrm.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nalzvkpl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2crzbdjsu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2mboqioel.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2mewejlpb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2wxwjkrde.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gt2chwcpzbq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mukshchu.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2bytkllmc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2ocjlnicr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jadlwwgr.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2cdomwzbc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2fplwcfxy.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2wlhbywnz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2ahiidqsd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2gtssdtrw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2exnvhxzy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2pchvxgpg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2vnehpqbc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2kxjdzdnf.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jgynigej.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsfoqrje.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gt2wonuefuc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2kojrlhix.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gt2swvkciwp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2tprijpba.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xclhypgb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2eboxrttm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2wkyzwvnj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2iortgdfv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2zrcizkqd.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkwhswga.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2jmwfehlg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2euzahpuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2aztkynhf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2uuzbwpru.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2wrrbtjlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2buamaahb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2fvgkxzwk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2lkbueoig.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2euzuyxwa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2jgwhlemj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gt2sgfyjhmh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2gdzdxtca.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2yfkojnfx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2qfknqlqi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2mafbtlxh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2cqrzuecr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2gskdrrfx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lfolqxri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2vepfwrgt.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2cvgreguy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jpmkaqzl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2cexdpwlp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2ixaviycy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2dkojvvan.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tokspazc.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2yenvywef.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2ywjvozbi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhuhbxe.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2zyatnkhy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2muagzsfw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvhkywrn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvpzqaeo.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2dqzngsup.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2icpcyepb.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2cidcfcwk.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gt2bubtxehd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsaprtln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2mzaqpyxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxlsxefp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2snxvhqzf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gt2szwwkusl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoiraqp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gt2vwzwkzaq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2vrkywzvz.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2yrjsgdkm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2tlwgnjwf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2vwkwfove.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2jkwljgmu.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ychormdv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqvwzqi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2liphhpxq.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2xowzmdeu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2uowslgmb.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gt2sqkcjpxa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2hfhegyfj.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2lotjqqzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2fusecegp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2ooxjvwxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2mogysloj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2tmeysvdi.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2byikgdtj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2wtlizlja.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2oakocpzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2zxnikvkg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2fwcfeaeo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2dumnqcvb.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yeuaxxis.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2mrzndwww.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ppbwxmgd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2cqufjnst.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zksjkqtk.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2pwmiwnzr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2fgupwdyy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2lwbxhuim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2iizjftby.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2dspsqetv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kphezfuy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2jprfudws.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2posqjljd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2dievzehd.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gt2tdgxrnlq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2ulokpiei.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gt2atxlojmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gt2wmrlenlc.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2qblvtsnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2suahmqsw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2pksolpbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2rtoksudz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2zkzbabll.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uabhttog.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2hltkqbiy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jzjnlfif.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gt2bzcocpoh.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2irlumaet.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2sdtqjepw.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2glgvqjct.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gt2efwgyywa.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2rlixeccm.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2utkioafq.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gt2lccvedzm.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hqrvfqwr.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2xgqevmql.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gt2zpcmbykg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zuashiax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2xriabtlb.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvtvfyfd.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrsootwm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2ujfphcxr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qsytvikf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2rtjcgzwp.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2ribjpwzf.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2gmgwtory.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2dbbqpbha.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2cvokodib.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2zgtqvgki.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gt2madjcirn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2umpuqxao.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2clryftxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2vemwpotv.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2cjstbccl.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2jznrrmge.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnczkizp.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2nacxxmwp.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttufpouu.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2tldjvwee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2hsmhjsud.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2ymzwnksa.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2yqjgejcb.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gt2hillbypq.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2qugehsrj.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2qfukfpdz.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gabzvjjn.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2xnxidxic.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idxrjmhf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gt2ehgpqdlf.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2llgtddet.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gt2ybzaeldu.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvhiyfcb.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2qwgfrsvs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwjccle.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2zangxmfx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2piclpmsc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ophtbetj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2hkfwbaqr.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnborhmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2jazmpvgy.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gt2ojkyfnop.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvlatbbr.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2nascdmnj.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwhgonch.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2ndbtpnjt.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2fmvrakqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2xnweapwg.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2shjfcshz.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2tcacgser.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2zfauvgfx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2bvyosark.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2gjdbaydn.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2rkvjgbdm.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2agozwxxd.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2mtempolo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2yvjggtrp.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2cnwbcwqh.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2wecyauhp.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2hvmlyaxn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2fpobrpci.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vsgnadwp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2lloacjvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2tkkebhvq.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2aycfuaji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2iygijdft.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2yupohixg.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gt2amlomufk.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2hfugmsan.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gt2mwpsbujr.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2zkmljdae.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2srzrfwll.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2vpijbbgf.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwcmpvrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2daruaxvb.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2owrbfgke.html


<!-- 参考信息 -->