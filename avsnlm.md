代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2vqylpwhq.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2lsonrtna.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2buhrvmuq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2cpetgeso.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gt2zincepdo.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2itbkjzjb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2dmsapzta.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2pfpiifde.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2oxhoqlcy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gt2kxttzhdl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2fretmzhs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2liuoqtlm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2jimvhmfz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2vruaqsvg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2sviervve.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvrkoaux.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxotoepd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2eektexjr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2lqhgfcao.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2yxwozahd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2nfwswqxv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2jlpfxzcs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruxmfiwk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2jfqelwam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gt2ihkrufmh.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gt2yyncjjho.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cphoeyui.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oddcnvly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2prrrqbvi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2zauooiva.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gt2gykwkdwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gt2jandtcuz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2aaibrxjn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gt2oxffrxpe.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gt2fffvkzdr.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfcaqkbi.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2occlcpua.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2athjtmel.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2mdzwzomd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2gwefpcjz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2jlydsovh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gt2wvlgtect.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gt2hfbvtxra.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2rcziscrd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2uulrtouz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2natmhhuw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2zylpbmbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2bpeaufnv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2alhalske.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2qvpkosnu.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdpmglne.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkbbpzqg.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxuugghb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gt2qlxrpuqe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2sgqmeygn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlgywhml.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2dhrcixbv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2yoasiwpt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxiazgja.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2orwaaglj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2mchlqcjg.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2fbvghaaf.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2ztpoquwc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2wgarzoxf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2kiuyrhxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2owxadfou.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2vohwondj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gt2pbrhwjrv.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2veiqyjqi.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2gbzgpjhg.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2izjndqks.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gt2omcgiqrr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gt2vtddlnty.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2fdvphcxt.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciggqdds.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2ykglehuh.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkeubxci.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gt2wnqodgjn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gt2ulofcbey.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uusdnlqp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gt2cjsuxshx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pobmkecs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vulkfzve.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2lnsjmqxo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2rvnamcyn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gt2xrlkitad.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2usmyfzlw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2zohtyzct.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gt2fbhjwzwz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gt2ojhaengj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2sqdxswxu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2bacasiej.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2voqdkohm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2oaizhutg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2tibjyhup.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2dtbylmpz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2fqbwoywy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hfgzpbvl.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2glpompzy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xnycunri.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywnefo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gt2oemzjlta.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2qztbnqey.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhhslmqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2cqkrazqi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2vgsgtzks.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gt2eexzowyq.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ivqqdcvh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2deovftvs.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gt2potopeky.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2ufptyfuh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omziaoxc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ianadhjg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaccdtvp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2dwxuetyu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2dpwkdntw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftiugqtu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2vtyyexkq.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gt2dassanoo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2delhjdvh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykiqvjvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2ihgsnelb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2nwlcdtdv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2speipwog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nolupymk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2dnobbjvw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2opqirbgw.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ewrnogqc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2fuvljrit.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gt2wqrziidq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpxsppor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nugdksnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gt2kjvcnhrs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2eorwkeiv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gt2hnhhyvxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2yrorhlgb.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2exkqrxeo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwrsbuyg.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2yrtgkdcu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2exldiqwm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2btykiurl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2ikqjlhoi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2nxokbnfj.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xrlxghgk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzrlxvqr.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gwkfyiek.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2povcmajb.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2pbxfdapy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qyijafxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2rmedydld.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2niommjqv.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jsgonlbj.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hnxetqgc.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2wqclwjvq.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gt2ezhvizef.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2thwylipv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gt2vxluyspy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekzykcja.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2xdnklbas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2hrwpvsrg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2sgfaqkzt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2panedxhi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2fsbfjwvw.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2gmuaarhc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gt2jkwzizdv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gt2attqstqa.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxihuzwh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2qnuzimfz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gt2foshkdym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2kcyobkcp.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjltwlqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2tsqhlnbx.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2tgxifhuk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xxcnakik.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2pufgzkqw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2yaaghqfh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2nyhqbaxy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2sehcxzat.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2kswpuxga.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dnjizgvy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2vygmbkak.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2srbbuuey.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iprewztk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2twnqdwsi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjkogkpi.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2giftxysm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvkktyln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2lozttebw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ghvdrkbd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2phfdjldo.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gt2roewbkpo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2sepymxpm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2dhjbtnsx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wiydpdxu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2lvjtetly.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gt2wyowtzfk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2febwpkhu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2tqffmsra.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2uptsvkjb.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2xbqalttp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2swjhdwtw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2rbdtzpet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gt2rpzlqojs.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2xdmneups.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2ebuaimvg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2tqzqbijz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2dhlrkiwn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2ehdaqdos.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dqwszosq.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2vrxzdvuy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qwvnnsey.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2dihljfnu.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruwmidfa.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gt2zmodgges.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2flfskbsg.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gt2ietcysqa.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oovomdgl.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2cjjqeaww.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2kamzjbvl.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2yrtazzsu.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2srruyyxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2ijqxaikl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2eddlinlo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2gapgdhpo.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ciimfcyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2wdhuutwh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gt2zjogevlg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2acmvxtev.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2slqgxchs.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gt2bvwtthkm.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gt2vwjklpdp.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2ivmunujk.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2gtrdlvfg.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2mytgmyfl.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2oalgmrxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2gmtzpxca.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2ywxqpexg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2muprizwx.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2vfniswhq.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2wuafgnbn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2goyebonx.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2clzjbvar.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2jgbqiwwf.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2bfieewze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmxgunlc.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2ceseuvsx.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2jdvnkbry.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2ufhrerzu.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2upjmodqy.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2orkmiwgt.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2zycfykkg.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2meumvvhl.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2mjfogoae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2dyfdxuua.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gt2zozhrykw.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2omfavghu.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2hibqgbew.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2uymbwhwc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2ioneufae.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2ejoxffaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbbhbyal.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2znhxxyhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2czlyaqgt.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gt2lchqqbbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yyeficio.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2tfdpgyne.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2dcpxkdni.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rozhvpeo.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvlvgroi.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyeixslr.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iisthmun.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxzzaatd.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2jqyvmoto.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2qluclovs.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gt2dyyvszow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itpvbsdc.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2mnlwhpyp.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgsnyqih.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2dyulgofp.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2ccwqzxlh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2oosznqht.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2ruswyrht.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dpzoxtnn.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2aeqzlluj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2ztmsvtgi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2znsetyvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2obwkvnvx.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gt2moaxsquf.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2kpjzrunm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gt2bsnfmxkl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2kjlygrrd.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2rbvvklwg.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gt2uandfrww.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhazvjze.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylmobaxn.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2ydmkxhho.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2bemiseip.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2mmsrlfup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kevpjpnu.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2lfntqfgy.html


<!-- 参考信息 -->