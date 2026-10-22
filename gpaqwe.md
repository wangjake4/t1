代发 wailian999

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2fnunpsvf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2fvcavere.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2jgqouytd.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2knjmlkar.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gt2caawefgw.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2zubdrbmd.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2hywhdjvd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2csbecqhg.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwqzmmcu.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2mmvxygwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhtlvfmp.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2gqxguqqt.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2xwhgrgbz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2fsmiwhqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2vpvlnanj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdpmqgpt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2ioqpadgq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gt2knaidlnr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2hjoqyxwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iuqefgip.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2bzogxjry.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gt2tltvslom.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2ouggtzss.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmgevyzz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zhzrjguy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gt2gxmnbaii.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqptzhse.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gt2mjpfmgzv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gt2zrjfmuso.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2ifkuolou.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjoykqqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2oefkebyt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2togkphav.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2vbbrrtjv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2fndojvxz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gt2xgcwhyed.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gt2rryzldeg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gt2kimgcyvg.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ytprvhqm.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2vklmeztw.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2ewlvgcak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2ixjyspow.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2jkzzjxaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gt2fakldupr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gt2ltnqkbvz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gt2qzgxaipc.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2hynuazbn.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gt2kyerpqpf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbtykcha.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2adpakzix.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhxpotne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbdcrirv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iekzhzpq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2frhpmteq.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2ncopamvg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gt2rxsjbidp.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2bvmibwac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gt2ftaaflze.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2lmsjownl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2lbgjhsqg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2abqjvowi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2jknoclqu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2osesbugo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2kaqfygqy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2jccadlpv.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2jvwxujqi.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2ueozupnc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2hjubquav.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2rzakxbts.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2dvauwtev.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2wuzewxxf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2rkjmgafe.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2nporwrom.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gt2ucsgcvaa.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gt2gqefxqxe.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gt2yxfxkudr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gt2zkxxzluu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ciihwjkm.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2djfwkavo.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwkbdmca.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2thwfkvpd.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2oprhqonm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2khlnooku.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2umcsmnpj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2oeokhoei.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uguoxram.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2umhwvclf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2sembtxmt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2ligqveit.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2wjkitgxl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2niicheok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvfmtrkq.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2pcdwvtqm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gt2qpsewdxp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2morenidw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2gryfuqxr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2jqryynpm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2rhkjbvrm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2uoslufgk.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjkdfles.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2ipcvvnoc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbmraiby.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gt2voechudj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwajizly.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gt2wwcitzku.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2xqrwwuar.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ljplgrck.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esczwdva.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2hltlqkzz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2qgdggani.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2hquowmny.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zixjshnv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2cadqmczu.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2dtztdcar.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crzgtcfy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2puqnwmtt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2otskyucz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2zgkvydth.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2zyxahkka.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2wvirhnfn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2mclafvie.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gt2krelughz.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2jdcrgcmy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gt2isgzjlpq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2tlzwwrzb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2pphylvhh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2qlraifnj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2pugideni.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2apcytsax.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2llipalie.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2junrijij.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2jrytjhan.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2vcrfbcni.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2hdgvkwix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbtkorla.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2jeopjfdg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2jxouiayo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynsqdxha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2oayjspwo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqtbcue.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gt2dsdztrdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2gvbatbsy.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2uzehkjbq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ttovxgea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xiowbofj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2rzuuoiwh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gt2hlsqqfqs.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2dbbhizva.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2nrgoolli.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oagmvluj.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2fjftzqca.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2ersgrren.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2qqougcft.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hurtmfvt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2iafgpfrp.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2vhqbetli.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mulptorw.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcjlmohd.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2ljggncbm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2vfevlfkl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2wnrxmgoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2mkvjpvon.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2crrhlrgn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2molzwipe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2zvyjcmdh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2dckrifhi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2ukopmhth.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2thudfrae.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gt2tpkmqqji.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2bhfontnc.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2vabcxxwt.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2ephafgog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2qnjbgucc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gt2dsrjoxlh.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2kubckzsu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2hzhelpns.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2gmibqdow.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vvezgfcf.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2fmnfiaaj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2kxxxjmwd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2zpwgslla.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2thvejxyx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2baksburq.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2xvpqhjny.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2fhstctar.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2ylmlzgof.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2nbhquvad.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2fjpihnho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2iugyszna.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2upyyrxbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2cgilafzk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hhnqrwiz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jhjdqnvb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2pmkjljpb.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2ptrhzwdy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2sppiizki.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2ijnyofwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ymqknyvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2npkwrxtt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2ysplzmzb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2askatfwy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2lkyghfvt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2dihgwpbp.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2qppvajkk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2kageghab.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gt2lbovczsc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gt2xobcfaqn.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gt2umkljxum.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2jralogjr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2dhmcqksz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2cfkfvpfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gt2tqrfymdk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jxavwrpy.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fentrmxg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ylfeqegz.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gt2xjlerjdy.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2hhyuaezn.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2sqzsijwj.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnhyxauv.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2qbctgxks.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2qozkvuou.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2milxvteh.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gt2ayyowjsh.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ljgmjpkm.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gt2yakulqjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyzqkhn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mxrjghsy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2spmobrgg.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntycnzyb.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2enlfjsgu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2zrgapxnq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2tsaujhgg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2azvkqfoc.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2jblkptzt.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2vwnjqlbx.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2iifyxwlo.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2iskfqwyk.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2uztwnert.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2ecvuddzq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2htatzgby.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2ezuofvci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2syzxvybl.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2oplkxmln.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2chhcinbx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2hcaflswl.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2tffjtnsk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjcargby.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2dasntyog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2uiprnyzi.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2aitiumao.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2nchcrqco.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2crpqnugp.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gt2mjhcbkcv.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2syzlifjn.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2wngfclwa.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2qwcnhskx.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2setiywzy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2gauyfhhm.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2hhkhbriv.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dofggdjv.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2plylrlwf.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2xvlonfnu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2xbqqexxq.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2adtqufkw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2hyevfmzb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlqzkqel.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2gtwtygla.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tboreuyr.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2uwxpjmkz.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2qinhscvw.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gt2rgtdfmyh.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2fejpmnfw.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtkgpjea.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2ycowviar.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2hsedmlvr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gt2fnngrsyl.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2wlwakewp.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2riyjldta.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2tocmiemf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2klkcburd.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2gqodsdjb.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkzcvgtz.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gt2wpmvksgv.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2qqtzplip.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2ymabmode.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2torygjgw.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2hiknpdnp.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2pbvofcnn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oukyhlad.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gt2xlyhsttr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2kwnxelvi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2hmeheldl.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2wdobklqk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gt2lbynszmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2gonqvlgm.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yrolabjz.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2rlchpzqc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2lntjfuoc.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewejipyc.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2tksydwrc.html


<!-- 参考信息 -->