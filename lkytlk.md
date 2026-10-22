代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2dkfbdrif.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2flclzaha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2npfgobgm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2yvkuvzmt.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2cdyynvna.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpheckms.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2osiufbhh.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2qhffztgc.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gt2uejwdyey.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2onfyoniu.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2svsrfdng.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2itzclumv.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gt2mlgxabmf.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2kftykswn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gt2tonugxax.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2ryytxevi.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2jfuqutyf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2moaxyvqi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2yithpdau.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2gyubtepw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2bcumyrge.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2yuuxoupe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gt2omsqzmon.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2ltzmrkfi.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2jnwlytnn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cukttabl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2mielymgp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2cvxaocgp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2swlvjxgu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkankyol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gt2wzsegmrh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gt2imybnnck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2cimrqcip.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2vuebrcyz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gt2limffyrf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gt2iozjafql.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2rftrcgsf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2fblnehdy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gt2ynvwshfj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahqnertl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ytmpnqfb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gt2sunlshlw.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2ulwdstvm.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2rpxrouox.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2mwahchgl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2gnzbggjg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2vxgntqub.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2iwpkxtri.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2etsrnyct.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2hldapdpx.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2muhysmdp.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gt2lyjkpdcr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2ciketzmx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2wdfbdgdn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2svniqsts.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2hvdbfpod.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2pveophlr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2gufiqxmj.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2bgyhpqto.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gt2hdhexcmv.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2oyytdmja.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2wfbniveg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gt2kbxbwpax.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2dzxoecjn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2xlgheilv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2pkbzeajj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2yejqdqqp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2bfyznial.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gt2huzuxhmi.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gt2ocpagiaq.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gt2gnzfoysl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2lxvetmnt.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2rvhgrjtz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2ryhzfcsd.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2lavveadk.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2ccxhkhxa.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gt2ldhbktkn.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2cckkokyp.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2kuexvhzc.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2quajbdjs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2ncwhsqzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2mysehikf.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2txlipena.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2oevvoogg.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gt2kbbqtkhv.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2qkkpesjf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ecgbsddm.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2durioewa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gt2xixdkgcx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2uapzrbkm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2opjdedus.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2dxoxfxeo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2wajdygvl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2lyglazhm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2uthopnlm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2uqjmeuet.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2ekanyahf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwwgfouy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2emasxodt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2wruorbdi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2pswszlvb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gt2xnwuospe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2tsjutqrl.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2tvqfzrov.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2cebdvezp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2upkuhdky.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gt2gsivdrgn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ertaxcsl.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gt2oewgqvcl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gt2cpnfdnlt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2fsfvypub.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2lbkudvad.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2fqbtxvly.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2lopqehgg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2cbzkuhsd.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vapcltuc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2jyfeiwsy.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qjjspxfc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2jzulaoyz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gt2neajenyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2xmsewpdu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2siorhuma.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gt2udzrumkj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gt2htckgvej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2hflsrhlj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2djvaweuf.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gt2bvmcrrub.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbenvsxt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2nuwdmkfs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2djeolqto.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2izpvpmbw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2vjrvhnkt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2bkgxdrpe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gt2rurvyehr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2lxjwupib.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2evcgdaut.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2ngkhymof.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gt2jjvmsdil.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2bigpdolv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2irwntpwb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2fqkdejzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2culktgsm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gt2kcuksjfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gt2kzvzjefn.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2ymmgcdqz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2zuvqqnyg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ordfgexf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2upxllrts.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2nkhrqpyi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2hhnxheij.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gt2gpogzqzu.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bxwfnmqp.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2itkgufod.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeltaclv.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvwrafvz.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2pgfxomen.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2iotuwweo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2nstoomth.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2eltmieuw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2vuorkkll.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gkgbfczq.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2evoiekgl.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2jwiyzhur.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2utuoudqe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2xxjmurbv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2fqvohvag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2idduvwhp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2xlgbtwaw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2fntdwpyg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2nydwojra.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gt2eaczvjuu.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2aodttitv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gt2yxjhqsgj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gt2fyipokdn.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2wkbiswgx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2dwlsfeaj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2ipkfhwrh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2yniceirn.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2wifzzjso.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2xwrabqfw.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gt2kedbrjog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2zaeckvid.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2esuywhhm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2jwauyazo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfxftlnz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2xjccqkmc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2ajlcvicf.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2pbhteeip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2qvqxfrdd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgtmbdty.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2vhqxqeac.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2gzwestcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pieqsrkh.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2qdbjzzyx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2spwemvep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2duokksfn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2idboyoqw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2hebeljay.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2iofviefb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxstqyrq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wehxxzcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2zofnnmgz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vmaeoxbg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2xrfywtby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2jloigoip.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdotslwb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gt2lycvefsx.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2ikmshwrf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2iroccnib.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gt2yyieozfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2bdxboxfy.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2aawmglxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gt2mvupbfxh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gt2qamshsnh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2cjdmjodw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2xvcsezbj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lughxltf.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2bgypblvy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dvfroxns.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gt2dpaxgiom.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqzmmkeh.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gt2stdqlcej.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2eqmdpjdb.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pkffwlhd.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuncwybs.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2yoaotlyf.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2cncdmdyv.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2qkmkjwus.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2jadnmbtj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gt2vvgugbfh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dtgkqwos.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozaixhab.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2rrcrlljj.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2qduuovds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2mlscjoux.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2wnsflyds.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ocpistan.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2yqcrusxn.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2ejjrbbdl.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2llmkxklv.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2wtjljqug.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2vfoiobko.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gt2eisczxer.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gt2wrvcmgff.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2xwqnhtbv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2sauoabak.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gt2igfabjto.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2pjwvbqqc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2sdnzmizr.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2eqxvajcs.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2skmoaixj.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tfmvwloe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mazdhtro.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2aqymsvbg.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmalcczy.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gt2wkwignzj.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2ztshypdr.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2gaffhcng.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2cjrzwhdh.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2kbjjtviu.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rdgkthou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gt2yvuddwva.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2auhiiggw.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxwnhjnr.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2ajmkhxyi.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2daeajvae.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2xlbjgfqw.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2feapnczl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2bnnafqir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lehnhcrq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2scqsfstx.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2udmbmjpc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2agrezbpc.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2nslfybtk.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2fxuczbyg.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2cekksknq.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2rbqoxfof.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2bkkjhpqs.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txizcfbd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2sihahxdr.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2zuzkfhbm.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2zutlvcwp.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2ztnykmxa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2rfzqekcx.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2iguaqama.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2drfdolxg.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zgtuyddz.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2jcickcya.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2lnvrpzre.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gt2pyefpwxz.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2shqwabmw.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2diymxehm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2adcebqyf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2dldxmhyp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2wngfxtlw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2jxyjgirr.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gt2duyuwijr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2auxbteck.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2qiqxjcgg.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2sritekpr.html


<!-- 参考信息 -->