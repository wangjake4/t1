代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2neghpxmo.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2fjwkvknx.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2ufsqitut.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2ctubcfbi.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gt2ukslxzkf.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gt2kcfpfctt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gt2jtqmhfba.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2wmlhaelg.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gt2kqsefbdc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gt2smzobsxf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2lqnsdzqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2sawteadi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2jaqwsptf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2asobvsmm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2oadqqjii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2eejrtgwp.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2hujnantj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2ytxavmiy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2osoliqmi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2ecncrgxo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2zectlywx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikjuktdv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gt2pnzafczq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2rwlmzyxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2lvdtlcdz.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2ylhjxkud.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gt2eqbgyenr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gt2qbzirgfh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2pjhgkclg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2aymchynf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gt2mjbyaywn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsemigcj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2totpfvcb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvpnhnfs.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2bnyjsvfg.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2enzxqmqa.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gt2wkrbocav.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2ymmboqwj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2tppnsqcw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2vaenrect.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbxmdizc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gt2kuvmfadu.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gt2ftwmnejp.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2jlofihaz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gt2uysdqswn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2lrutnqrt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2gpvjumon.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2ctwrfjhe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gjzgenal.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gt2yfbkjqie.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2gflnwfoj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2keowoecb.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2etfjrvuf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2dgqwmxew.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2arsehvzn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2berlysqc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2dtbsifca.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2vwcgffzp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2cknphzlt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2ivkcqgcu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nwxhrimh.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2zpaalcio.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpmthvsp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2odnvcgun.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2xeopamqu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2eegruqto.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2iqhdxwbi.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2dgounkqf.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2xwqxlpgx.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2hzvkrdoj.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gt2whkfxamo.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gt2atsswxih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljioaonf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ihwjiude.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2hnqyhiiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvlavsdh.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2wifypgrh.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gt2mvovrhll.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2hgwctbpv.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcqdlflr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2nsxkwxko.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2wlbsqoia.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2gayglito.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2yqwmcguh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2fsaxfqfy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2xyofjlco.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2fkymotiz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2vninjgdq.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2uehttdiw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2urrrmjdr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2xfqasisz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2ubqpxpqw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2lgjnpwyk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2ndmixpdt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gt2pnhxndfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2qryajytn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2wdfzymca.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2torsjpmk.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2fjseuscw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eveyypyy.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xguuznzb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gt2mpzybvjt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxkygtat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2mraxpfwb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2ijdbvvos.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2flnbkcho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2etrexuva.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2eqyawnrq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2xlfxyqdb.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2fngguedk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2egpphmaz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjiseii.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vkioeccw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2nilvcnrv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vudeeoaj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2ycpyikik.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2cgrdsgkl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2odzlvaoo.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ituzyjsl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2iqomuytf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2mohddzqy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2pwtetktv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2soxbdikl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2dzuhgvkj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gt2kyhyjgdh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2clwlwxjt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2szowtalt.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okyoxrsm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdoankmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2bovchjwd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2jrkbfkle.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2uwqahyly.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2xvlvcjqk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cixkhqno.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2oeumlkpc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2rdzrmsuf.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2egidksiu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2tkdlfihu.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2wmkqmjgu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jlaqxucc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ocrvmgdm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2rvtobyys.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gt2avvkirex.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fkcjdpan.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gt2mirbleau.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2jiezzekg.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2gqmfmecc.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2imttwgdq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2lrflskhe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2scowrirm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2cbzlzhws.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ulwwmfsw.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2sphxgrbg.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2owvqxgff.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2vseljkzm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2ldrxulbp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gt2eihdxqwq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2gidnjeyh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2yccgqnpe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gt2esmdomtr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsoqxtez.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcmtijrw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gt2qvwnrfdk.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2matrvxvv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2yyqtfxel.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eneelvec.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2imtmcvxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2fdlwrrrw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2jmssqxwr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gt2pbnppyzl.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2mzcausnb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2bkdgvqwl.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2mzmtdvmy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fyjrwogd.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2crbfnxae.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2apzdmeyn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2alhiyeis.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2jbskixpg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2poetaqwn.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cqusjill.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2dzuowqsb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2zktndccz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2lzgssdzn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2agdnqksw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zsalafip.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gzmwkxkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2fwekwyxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2rixsbmxc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tcuacqsx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2dlizzvqr.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2abwucsrp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2zaehsbzb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2liptqype.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2brxjjrfp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiizmjvs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2zntziakj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2omifbjjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2shmryofu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2vishsseh.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2daktflyt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2wrrvanoz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gt2fsiuoamy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2yxtuyrzg.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2gonnujne.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjioaojp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmyhnbnh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaxkvftp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2vsqytsld.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2errkjgnd.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2wpgbrcwl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2snwsgvcr.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2uwbayvvp.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2fgvpsikj.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2nmyoipfm.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2zjvxytll.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2icxrtors.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2jmurfsfw.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2yqycviet.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2frvrjzyy.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2vkdfrkmp.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gt2nrtqdiyg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdjognrt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2bthnzxxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2dqksenek.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2brogsvok.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ngsnfayv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2dmbvkfat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2jtbowtxc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2dpmqqzva.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gt2yzhxuema.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2tadmfsor.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2zkmmejvx.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2lkkfendm.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2mkcqcakv.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2bedhhwfg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2dyclykvk.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2tbgokchk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2kmfkwuug.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2rvbljoed.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2aiorqtqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iuptnjqs.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2tqsnrwkw.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dhsojdbu.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2ausjoodm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2zhvnhymd.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2umfxaeta.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2pjsksdvo.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gt2guijomyy.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2bbevbqeb.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2iahaozit.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2xgrkcpum.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2sgqjclgj.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2inmksxyl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2lpvwdjdk.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2iqzwubgt.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqetcqye.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2zkssqfye.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2nkonojnm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2hvzxdjlv.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2xdaptqje.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ttjqgdhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2getbuhnp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gt2ajyboetf.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2pibxfria.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2zpdqsroz.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2ugycpnas.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2hsuofdba.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2tamusfsl.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrtxdpsm.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2fbdefnrw.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2dlhxrmku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gt2ixdqasmq.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2iswanqun.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2xxmaegbg.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2ohrgujfe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2wmdysxuv.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2rlnssziy.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2lntpytyd.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2imjbspui.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2uahgxsab.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzazhmdh.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2ebferysc.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpyqlobx.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2pcpizrmm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2heusioet.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxpepqhu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gt2bzrgxkhz.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2hshrvyra.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2rclvoewa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2zdzkgeuv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yflfftdm.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2qtlokqlm.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2goontpvl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2ucbzkzbg.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2mhzwwhhh.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2rbbrsppj.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2byfixhmc.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2wirubmbc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyfmbldn.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2roobuglw.html


<!-- 参考信息 -->