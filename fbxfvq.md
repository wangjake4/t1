代发 wailian999

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtehdkpwog.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtfnuyhpdm.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtbntszacn.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtmbviqirt.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtytgzittc.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtnpngczct.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtfdiihyua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gttbbiokbh.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtbtqgpzyh.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtrjkeyrnq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtjnzhqcmq.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gthnjkqquv.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtesjclpdd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtbvpfuinf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtixajckyk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtaohcimth.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtyhvtabrx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtqzalpvbz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtaqekbwiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtdrvuhjce.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtirtrunis.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarpkqgma.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtylmrjtwo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtrmbhacpn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtdpucjjjv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtumuqnjaq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtdovbbaki.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtxrradgcm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtolseufns.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtalpvpkwk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtcdbhnvkp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtvczsutnu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtovpecysh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtjvbkamhn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtzzwesdou.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtvgbafcbx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtkuidhhyp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyrlkutcw.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtvikfmfiy.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtveueeqdb.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gtqnojsryl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtyvunpbir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtvwimrerc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtaeaxuwvx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtekjpdzgs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtugsakkau.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtfopdchhw.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtrtyzpetf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtapkburvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtfwyiesei.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtfxahzuoz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtfyrehdrg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gttbndrnam.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtnhdnubkd.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtajdssyik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtwsvonttp.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gtojnxogss.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gthzbvwyfv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtoswhedcm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtvwehnqur.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtdphaqysj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtiixinhrs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gthadxbbow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtpmqrxief.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtjxlfueku.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtqqkrsdnm.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtyvljcrer.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtohkyhdyb.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtsyjsppve.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtevmyipck.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtktcdwlkf.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtukprxaro.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtscnlqbcm.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtsxabvldu.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtziepbvmg.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtbmvrgfew.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtmssbyxha.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfqubojhd.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtczsagias.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtddfhomdv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtqzoopizf.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtnprznycr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtfujfwwuy.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtbtebntpf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtpajprnir.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtlyozrnoo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtrabftelq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtekyikqdr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtblsjrkgv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtkpjctwim.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtmcjphceq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtkrjdzwhz.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtwisjvurs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtnqnijvrb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjtmayq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtdocdbruz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtgstdudqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtrkhvogjh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtkcslpnss.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtylekangz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtndyslkvq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthdenttbj.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtcyucfnfh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyypgkkmn.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtpsfxiiiz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtkrxhjgcv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtijknziku.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtijwaoasw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtsjohaigg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtorayvbzw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlymgiav.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrpuxqdsj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtzonvvfof.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtvoqqhpto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtzxxpcrqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtdbikeurx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtgdssbzqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtbxfwaaey.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtlvuckufe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtuowlpjwm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtipwygstv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtcjvhfrtb.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtqaubqsyy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtdbealqna.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtzxpglaon.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtszttnmtb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzevfpoxe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtyfoesnwn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtpgdlzlht.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtzqwyoifs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtfwzadijo.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtxuvzhqof.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtjftatori.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtgmyndsxg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gthisjcvdx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtdalfcewn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwfuvmlf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gthfkpyeak.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtfestlzvb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gttkphwumj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtfdgkuphn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtequfihat.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtxayzkhdl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjsskoac.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmhvoghxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtrntnvtgz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtxaxutwtk.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrkezmgrq.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrnkoudev.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtkaiuzpye.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtimcodtxe.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtnhbsblcr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtisozcghf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmisqgnht.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtzctrpdjq.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsxxmrysm.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttnmxzaqw.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjshyfuqp.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtqtqfurhw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gttmlxdyfr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gtkbkzmtrd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtmhtrilkf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gthshdtwii.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gthpgcpzgo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtpryiajqx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gthjrmihah.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtrylafmlc.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtmlppfzld.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtoojpxexy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtfuhvcubw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtwmdeydqe.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtbncwngwe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtvfmrjfpc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtauqwajmq.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtqvbjtzhn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtlzmdfkqu.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtiuwezpcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdhgwenud.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbxqpxklk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtculsnfuv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtiqetlswp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtyqdsrryq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtsoxwfycg.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtrjgoozlq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtakwwrdaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtvzigdhmn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrtfwiait.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxlbsivoz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtevvpzsth.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtanatlgpq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtkilcinbx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gttcvihbbo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzattquit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtgpwnuvkv.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlqjyddtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtdwmqlnht.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtauqdvueh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtftdzcpvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtlqqnsasj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtvcgluumu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtorhnqspm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtgamxwdeq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtrjniryyt.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtxtcepgcj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtgcrvzhxf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtdznnpvdg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtpnuqtlcr.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtdbnxlpcv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtexudndby.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtftyvnctt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtreogeame.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtuzipzaip.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglswogfi.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtsnwkbqtc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvzpsbcgf.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtiklagpvs.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gthhlcuxdg.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlsomiyxs.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gthoyormth.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtxxupzgcz.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtpkpqbjjk.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtwhpvjbjv.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtsahrahvl.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gthowygkze.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtopjoljqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtiopuwayk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtyhbqpede.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtdjnikkhh.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtozyzirfp.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkczsxbok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtlbfemmnm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtajqmmmch.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtuhzltqhm.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gthjmdykjh.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtfwvuwwjn.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtrouebyio.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtogemagow.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtubkufukl.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtaepfzcsq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtdtxdkoww.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gthrybupkv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtnaywmcny.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtsbbunyuq.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtvocgwojj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttvppzizr.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gthfmlrrbw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtdozuuogt.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfplhbmc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtdkxkkeup.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtmqoxijow.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtouuuaqqf.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtmplrzmpq.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtwknysnox.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtumutkpba.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtchuumscd.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtiwvffidv.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gthoyfsaea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtciaszcfz.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gttrbykgnf.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtrecunhpg.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtvmvjzxzi.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtuzztwveb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtujeawskn.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtlvmjkhif.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gthdjjtxya.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteqzmlxxh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtsnatozgx.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtpxteploe.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtortlnxrp.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtlsgbmkhp.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtwmrrcdkp.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtmvipsmwt.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbrkgjms.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtygusrint.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtethjiugf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtorbbsluw.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtjcxdvgbf.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtjrzvegvv.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gttfmmhads.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtrzqyzrfh.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtaqnarnqg.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzbmibvf.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtxmkapwoh.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtdrjsydbs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtejjvsvps.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtdfgpfhea.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtmagkecex.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtphstxcms.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtgslgahfp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gttpmcqsbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtmbbkorta.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gtjfyobrsu.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtbprfkyut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtinektkat.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtoptollsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtdfgnying.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtrrqdjhlh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtabqhxriw.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtnvbnsqqj.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtsrhsilrp.html


<!-- 参考信息 -->