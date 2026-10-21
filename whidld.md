代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtojgdahbx.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtgbxktcgc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtswnuzoar.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtisevntpc.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtuezjxuem.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtjxqlawok.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtfmpgrpwb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtdfwxbkug.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtgfobyxjq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtcdgtphmh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtqpbflkcj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtvxymszni.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtffzozmsu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtdvaieozc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gttlthqend.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtvopiqjta.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtyfgpnitz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtkvwlezoo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtaeguweol.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtfazjqkdm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtqibxkopn.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtxojwxqzg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtaqwvrysh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtuqbyskda.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvdwsljdo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtkkjynfav.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtdvocahbq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxpdnuxm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtnhzpnspf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtidevhhmi.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtaeagkvck.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtyivudbxv.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtzfgrtyqm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtmpigwwoy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtqnehddtj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtfkjlinmw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtgntwceuy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtnqthenin.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtsvhhhdyi.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtasxsvcet.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtejwzibwo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtnvzfjpol.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyosykuj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtjzavmksw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtpevgrowt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtylfpuoha.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmdvmztu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtmwjotqdn.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtqzftjnzm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtsaqqouvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtwjnqwien.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtoaeqafjh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtipsktvqr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gttkmtuexz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtthenxxga.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtcrfyofnf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtnzszzekh.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtxakscjtl.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoatmxksy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtunzvcimy.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtciuzokkh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtjahfzsgb.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtdwrdbvgh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gttvqdpqyz.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtadxqseut.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtvbylhiba.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtqloosvbe.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtwgjusxkm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtecrtauwh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtnrmkrulv.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtjrdagfpx.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtrpduvlwe.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtwaokfexs.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtpqhuwtqz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gteulwghzv.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtvienhwpu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtmhthgbnz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtgmlvxjyb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtgagkkkja.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtomggxleh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtwsydjzsj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtumjmnoym.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtleiyekqs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtffnhdszj.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtyndpzgmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtcugilcfc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaktgbbo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqdeosmp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtpxqrutkw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtlkdukhwc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtpzdfehro.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtllmgwvle.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtiwpyxazr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlcnrpctk.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtasxmwzlu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvdbuezju.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtdacltaap.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtduqdxscz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtamsrqwzl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtlzmuptrv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtvwzthuai.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtpiowwjcf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtpdzrswzu.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtalowkrur.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdfmmkttr.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtpdpsfvsd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtskcuspqg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtysabseup.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtoionsgkn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtashcrugj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtskiwvdaa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmwypjp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtdgxniika.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gthmiqeeff.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtffzysmzu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtwiawtsph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtswtldgsb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtuzsbhmro.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtanonkddz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtkbmqxqiw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtzzuvuvuc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtcfqhbmjr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtcalidoul.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbhseedyb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gttqontfuo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtsrxztmld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtubokjrya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtgeowgjij.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtdjfiavvt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtzblaqppy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gthufpsjho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjryqald.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtsqiherfy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gthryyapaj.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtjxnuyktr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtmywhnlip.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxjvioeji.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtnydasdti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtclafgqdg.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmtduheod.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtygtjtaca.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtyyjtweqm.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjydpoqem.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtorxkrfii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthbfxlzsq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtuuekfurd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtrykyomja.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnojlifqr.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeladccz.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqrliziao.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtlbbttzwo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtrozcuhdz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtlprtenhl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gteohqfrsz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtfhmoraou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtkkfinlkk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtrslyrcec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrqdoowg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtxxrudqyr.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtufdljcpa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtqvccmbzc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gttfrqdhux.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtkkoeogrj.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtsuzrfrmw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtbgoorppl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gttylxhvol.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtmvdlypkq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtectaprvp.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtamtvptck.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtininzxxf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gthkwqqhkc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtcwgmnwdi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmybwshv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtmheiodoo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtteuytplj.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdecopswi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtqtrtjkpu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtylrskjtm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gteuyegevq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gttdikbibw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtecfwbgvq.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdextzdzu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtmhemgojd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbaxqeysv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gthnqgeotu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdxjeafud.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtwrhbxgce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvepuigcd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gthztfipuy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtdhaysoyr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuuoxgtbk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gteuthrqmy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtpzxsxoxq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtncyvzwbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtkqqhyrsa.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtbmcfqwmc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtijbixwan.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtgnducxzt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtauddoebh.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtuxhfligl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtspvywnem.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdmrhoqb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtpzusprqk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtpxhktmzc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwinbysaf.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfehpikw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtprfkmezw.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoquchjic.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtutlxghwl.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaxphsfu.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtxmutjgtz.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtthuttmms.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtudtyyjpf.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtdmnfzxyo.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtgpdfmuiz.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtcrdxnhpn.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtxsioprxf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gthetplatj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gttubrxqxc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtyowykqwm.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtvwrrmdte.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtpgctqvdj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtalrwofon.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtrirpmnsv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtkiififjx.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtvdnvhyxx.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gthczfopqg.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gttdtdyuxy.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtfxzffhoi.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtdjbzhase.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtjprxmvew.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtpkrfowph.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gttsoivaoe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtrbacoxjz.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukrjmlvj.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtaeiyusep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtwpdqinkf.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtjxvkiuxv.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtqeghuxia.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gthiqxcqso.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtenmadpdp.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtkumueqcn.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtdujoyvly.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtlppryrqf.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gthyntsudc.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtkqsdstmu.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtuhsmurkk.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtidvdrxrr.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtlhvagbkv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtnajqpznn.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtfgoeabxs.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtdxwlviom.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtewixobfa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtpmqohmxa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtjcjieyqr.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttsjdjgze.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtirmtaids.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjgawnkuv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtixirxfix.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gttlqytoxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtyzhbkoey.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtgnswgqjp.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtpewltpgl.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtbhmuhigb.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gttpkychnt.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtemluodgo.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtadarpfcm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtgqmufsat.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtnhlxkjme.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtagxoigtj.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gttydgsonq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtqblgpalf.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtadigzjzo.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjfigpbpt.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtvzjylbrn.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtmmjbjcfd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtxqbontvz.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtbvhdywuo.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtnfgteqxb.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtdqcpodmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gtmlyyimeb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gthvbjfhyg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtmlyatbdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtnrfxogfp.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gturxnhaua.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtityirrho.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtadfqgvfa.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtktoqjdmh.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtyraphoje.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtpvevacsz.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtzqmxjqiw.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtraynbqke.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtauswzirm.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtbaqrkiof.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtowsajvnl.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtguffcpir.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtvkjofrjm.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtjhxknuqq.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtjojmarlg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbcpwnvq.html


<!-- 参考信息 -->