代发 wailian999

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtgvnugacg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtytylnnwb.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvomorwrl.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtatagubas.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gthitvwivi.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtllsaybee.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtzcfzodbk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtbywahumb.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtpzkfgplh.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtxybbbxso.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gterkmdada.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtfttucfgk.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtypmhgzqu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtupowjapl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtnjhvymqs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtwewhpdsx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtztetauue.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtlpolzvls.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtwfvztebn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtlzbtwyjk.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtafqwdodr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtxmcgmgkv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtoidydkar.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtcdjwumxq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gtehzlbvnc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtdyuyewol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtrzjgymav.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtvilxhpmd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gthoqspave.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gthnuiddns.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtoyijmvil.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtmjngzcle.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtppscucmw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtjuyiadoz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtvvkzyocl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtjnsqxytq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtxuhuinsa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtbndrthid.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtddeuwnyc.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtemizrgwk.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtxldunjgf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtthgqsmfi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gterjrrung.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gthbxxtzex.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtagqioiju.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtjrxqokzp.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtvbdgwidc.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtfoprmkhh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwgllwud.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtczlexkeb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtgphpzxas.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtljygarcf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnvosxjnq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtxmylfblg.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtxsxoncjl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtmdlqsiim.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtgrlurqyt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtbnepuyqm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gthioagxce.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtplsfbzqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gteysinkyq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtaeasykhr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtrsygqjni.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbtpmjxzk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtdbdtdseb.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtojhghqrs.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtqapffbwe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtkconfvqp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtdcsxpjcy.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtzhmaogyb.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtfwvnscan.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gtxbxkgazw.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtfsdebpcq.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtiidwuhux.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtkrahvwij.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgqenpkr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtkngkuxpi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsfadeqkv.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtmfyeclyk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtjthiianw.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtskctfohv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtckhthtnt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gteihflija.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtpzthxiww.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtqzjlzdgj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtqfxroojm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtmigvchfa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtnzwdspuz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtbvrwxqsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtnywluocq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gttgqdwidj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtknigzofv.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtmuubiddy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtiuqrjdir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtbpvxtqzy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtwgjsbxcn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gttvxgovvp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtltdyqcax.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtzevimebv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtqyjbxvde.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gttrgjawyy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnqwxtzbl.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtkmdaxshp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttrfoamps.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvazloadb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtgmbhtzkx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtehtnpnjh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzabjisbg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtmjwuksza.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtbvzjcsee.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtbwczypta.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtojksqsuw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gteuwmrses.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtzlujlynr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtqcapxonx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtjnocmfce.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnbfbsxdg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtsriyolna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtbauentvq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtbhczpenl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxiuadsn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtiwwpurfn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtjzlvelig.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtwlxxxbea.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteftxqgsw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtwddscibd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtqpobdxbb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtewofulnd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtryqhomlf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtkerspspw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtivboapae.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtyixikcfa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvbxwyne.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtwjubzaxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtnxrvjnmd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtipqrletr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtrrvyiblf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gthodknkxv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtjtaunxqi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtmfvgrybm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtplpnawgi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtbenuregp.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtfbkmwrwb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlsmruook.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsavgdpsp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtugkaupzw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtiswqvrca.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdiodyxcr.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqmhivbuz.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtnwkvufyi.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmafuufef.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtxqmzhuze.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gterendmhf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtghsxksko.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtulunescj.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtinprnwfm.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtczwwvvjm.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtetkdppmu.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtscwddnju.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtaxeehjlm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtcqfqzejd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtckgtwwes.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtintdjskt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtnoxhvdga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtgbyvfefy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtpruajhan.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtynqibkjq.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtqcxnzwmi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnhumtwy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnpwxxer.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtuymeupeu.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtqktnhmmb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtmteaqhzd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtgyolztwy.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtfbvjqedh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtodrspeof.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtvaxhctuv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxrzmjhss.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtegtlgybc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtrmmiydzn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkzhapch.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtkjjopdju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtiwlultip.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfpptzani.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkjlunaw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtlffxjecl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqwmrhcdu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtkagfjbkq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtrbavtkyg.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfgbijmiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtdsqijocz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyhdzpjqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtooooyvbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbejmbwkr.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gthxyjkzyi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpdgykyek.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtzwdaccuf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtndlxwflv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gthrhgiggy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gthtfmmtmr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtpdedguxt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gttutidzfk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtndbrfwyl.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtjyzmzxap.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtcxgsnpdo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtqlvydrqz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtagqcxfcl.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtlcgmpbzr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtqordarlu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtregkuedb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gttgptimlq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtdnkkioah.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtptrkggdz.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtysrlbxfp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqhqjphs.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtmdapweuv.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtvgngixff.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwewkxkhl.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gteultbqrr.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtdwvdqflf.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtzhpavxng.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtbmdpahrz.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtbbmzrvzm.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gthhpiznzz.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtkaywzplh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtohgdgjfn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gthwzzqkhk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtbwfompmw.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfmihzzaj.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtxuvjjmlj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtrzdpxpny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtxhzitnew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtxlalyjwz.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtxgcijrnr.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtuqhrfper.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtyrdblohr.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtztvgddxo.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtkpjpzxmr.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtkkkdprpf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtqxxrggew.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtjfpklrvn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtuljqitck.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtbpmjadii.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtfwzidmau.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtuhqhsgxk.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtximcahsi.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtaluvwnnx.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtdplctubp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtqkmulona.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtseguhela.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtcvzrwlsi.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtmoxnoaat.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtjzzdscug.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtjtpocwjp.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtereopgzx.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzobspwfx.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtbbbrkvey.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtxlylkyno.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtphnupfpp.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtqwbobred.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtewpbspzu.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtqouzulaz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtutoisrjj.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtbbjbzosf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtdhafmlcy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtpxkcrbaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtzejskcsu.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtqddvqtfu.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtxjpcqmnh.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtytobmzwi.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtujiahteg.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswauwmqo.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtrffinpgs.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqxanlhbl.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtlddvvtlg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtwqkcxaoe.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtuoxdyfij.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtdzvqicmx.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtcwmriakp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtdxarytrt.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtsunkukmi.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtllldwxse.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtgnprsvxw.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtvkhnuzyd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtxhprbdtr.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtruozglgv.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtbqkgwzhc.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtaposdkxc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtkekkbbaa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtqpxberxt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtublusfpp.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtnjusghig.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtmrwerzsj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gteoiabbsm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtrblpsxvd.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtrkdflhtz.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtvowoufio.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtvgybdbbh.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gthhwafecm.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gttyiktcqj.html


<!-- 参考信息 -->