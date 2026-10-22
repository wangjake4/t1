代发 wailian999

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtzbrbgfll.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gteneywunj.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtcfqzerud.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtdaofpsjp.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gtuxqucmci.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtfxohkypl.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtzqcmvfiu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtufafnugp.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtmyleschi.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtixodixbo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoanwyst.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtefbrrpdf.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtjuyprktb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtisadfyhv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuzrtkqgj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtdkbuqqhc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbflyargl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtbimkgedu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gtckrmusvh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtrhzhbrgl.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtglnyrrzm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gtzvohazvi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtpqjnhypz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvrwuazd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaagmdoc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtvnejheyd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtexkamjzo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtjowidzeq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtmtzmynqz.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtekdxsqyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtrfdczbjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtwdrqaclz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtnaprblnh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtqixuyove.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtrqqnhvqv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtpgjugalt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtyjgndizs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtybvqnijq.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtfvqgtiac.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gttkjybpla.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtqtblsbon.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtklwspfvk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtejjxeiid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtsuruncvt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtfzutkpoq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtszoodezp.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtwqbbzcae.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtzlkyaezb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtnnhhovaf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtpughczuk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemwcsvcz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gttxboebgu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtahdvvoeh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtbrppsnij.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtwnrxpjyv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtxophbpof.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtvpmzevzp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtltngoowy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtovllgjwq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtejotrngs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtmhicqbxf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtxeqgqaqz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtfnevlqmt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gttagrzdli.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtsuryyivw.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtcxrirazt.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtfoytodxx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtmrfccdpa.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtphxrkfde.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtsurtmfst.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtsmukuklj.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtpwzivauz.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtngwwtaxt.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtfzqignwq.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtgqokaggl.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gterhyvpbn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtrebwpjgx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtwfkxwkra.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gttvtnqkho.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcydjuzmq.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtklvmamce.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtzqdfoqua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtmfusihke.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtqjajesvj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtutwaabed.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtkujhucte.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnubcukkn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtupgefwxm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtfofoxcwe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtkbespsth.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtvuxwxxlu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtlceumhoe.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtrjsyvhox.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtgvdnxyqv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtgnyjwcck.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtdozaxiiy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtkfnutpwo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtvvuekrcj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtokdwflcf.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtgeapvohu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtyrqxyzpt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrmgeshnn.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtmjvnirro.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnvondvom.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtxsxbgttu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtwezqjexa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtnbbhjbiq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzgmkpyc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwfigzmr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtsqqalaam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtgubuiret.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpjtbokye.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtdzhraonr.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gtyypldyia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtanigtryt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtecicsanw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtrslvzhhx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtkvlvsuej.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gthuvgovac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrnpkzih.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gthwujwmkw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gteamscaqe.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtewgitboe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtdsdjyinn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtftvgqpet.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtruycsxfz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtnzzybsfk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtwlsqiiov.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvitdrijs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtnzgrlsxl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtpdujbpdf.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtldqdsyae.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtdemjoxqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtetvrrrzd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtvkynwwky.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtkvbcmlth.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtfvkroiqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtfkyychjs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtqxtprgpp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtfgsffezc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkhzlhpc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtlrovryjj.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtktootkjh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgbiwyywb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqquprhwa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtoigjeoaj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtdvqagpqm.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgqvodztt.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthlydlawn.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtjnjapbmw.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttbxnmcep.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtimrsizmb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtluqbrsjj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtapmxfqcv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtmeuemkmh.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjtgqguks.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtoojjcwfi.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbmdtinin.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtwihryihv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtkiswwaku.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gthjeisblx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtplfbgfvx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtykmnkgyp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gteiseyqec.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtmbilxmco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtpmauoejx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtsksiqefn.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamlpckzt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gthobxwnfs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrqejilwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtsjbvxapa.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtczvkaors.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtzghmsekn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtkqzckoug.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtnvocvmsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtcadgykxe.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtffxscycb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthzxsbsau.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrhlofgzk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtjswprtqt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtyqmaksys.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtrjolayju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtmjffmmhj.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpucxewzl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtmqwqcuma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtsxogmall.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgrsxbwgn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gthndpaozk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtfeykgntk.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtszgocfjb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtrchnsrit.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoeggjlpa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtnsctxnwx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcjdpleye.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtsniosaze.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjfazkblo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtglubqnmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtzoxcapce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtswmgbmnp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtdckpiepk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtnrgmorhz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcrcwtjkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtktkurtnd.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtifxanbru.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtjhdwxkvu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtplealmpp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtkxrrdcgh.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewjoxhwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoeijuev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppjhqbmo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtfhiuixbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtslrkrzyl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfmeaeeyy.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtyetsvebw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmqaojvis.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtwrfdvfko.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtyrtanqow.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtowflvwej.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtyuealevt.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtueynfmxc.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthufrcmhh.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtwxufzblb.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtgeizujdw.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjfkkngdu.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtvecmvywx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtmabqhzfs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtrpmbqkzi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtuhnofdnh.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtlbcvocvf.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtvwfviofs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtalxxyjak.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtnufyhqpo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtiwgoxogc.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtnkxpphso.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gturrmlrnw.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtgdmigepj.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlapuxfp.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtpegnlrce.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtnblnxwvp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtevrxsuzi.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtppikgsnz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtczrclfcn.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihkqeojr.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtaqwueskj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtsfqikgzu.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtjvjivuxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtwkdfxhqq.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtjournkwm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtzroymiol.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtwvtmixhx.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtcrtfjopw.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtobujyfrh.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtdoqyaaad.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtkhpdohtn.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtgawhceah.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtinztbxvd.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbnfsmddb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtzrjxabaq.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gttvabtgwc.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtdmrxhiih.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtesmcbudl.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtojuoqrlv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtddybnvhb.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlyzxutch.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtwggalewc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdvhomlv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtfvtflrjy.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gtvkuqwwwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtjqrabtfb.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtxldzrqhh.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtdgzplyzo.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtmegzttil.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtmfbvixkz.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtirpmiwwi.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtcleqjcwn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtkoawwwvz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtnfynavdl.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtaiezcovi.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtndeszzic.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtogrrclym.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtwtnhiudw.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtlpmsglpw.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtogjgmcps.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtwkzwaqkm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtssvnzuvu.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtpdrxfcxx.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtcjfdjpfv.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtkrmpmipp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtqfhevzcj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtjjalybzf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtldgsvnit.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtzezjmjba.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gtwxfujkcb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtfxpzrxjy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtxwpjinpm.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gthydaweea.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtwffeqtzv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtrpbafxer.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwgznxru.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtcovwxobo.html


<!-- 参考信息 -->