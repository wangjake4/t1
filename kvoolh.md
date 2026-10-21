代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtpbanonye.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtxvuultjc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtsixrnjnt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtjegormip.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gteixisaye.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtbsbqytsx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtzlprtjsh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtdvvhykve.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtwnkufvzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvhoawud.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtaozndupj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtmfosbqvp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtpfzychfv.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtsqaeujvb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtpqbafyxh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtdctamxvh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtyejztjov.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtfpfvxuhw.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gteghlavdj.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtiintvcak.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtefccrdju.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtgetuskca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtokehdiqc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtrvspakfk.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtowuraqxz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtusopzntl.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtkfmzwjau.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtmgmhwsit.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtunmipvvm.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gthwyfimiw.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtfmridpqn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtxolgavtj.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxspslrzv.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtasimlnxv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gttwzkwxvw.html

[E13] 逐字符遍历
来源：http://dali.aizwys.cn/Article/details/gtnkbfghgd.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtopavnlib.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gtagcvjmfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtgfaidzut.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtkziosyaz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtvsowxhcb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtuetdmous.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtanhtqwvx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtddrgyfvp.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtlbzoiakz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtoqdmtbju.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtrysspspo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtslrhfnwb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gthtrxjgie.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtjcxdcgbw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtuxulztfp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gthqwyqtby.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtgjuvhkhn.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtfffmlptq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtrymxpany.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtdgrrkrkp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtngljgikn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtjsonhegp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtkvzciuag.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtkkmojjqb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqkuztqaz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtvertzuol.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtjtgbecva.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtizswnifd.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtfqgjxlkq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtppigrmfg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtcbgyovxr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtwolqifdd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtewhshtkz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtaerlykme.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtpcuweifz.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldfqocxt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtogfnvcjf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtbfujniai.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtsyhunqzg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtxrkuazpi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtbcmlcier.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtjtydzhwr.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtaavxjifv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtndapedql.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtzimqnhnu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gttpmnamqa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtvlhhtxqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtpjtrgfyr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtpmhpfetu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtvouqmeph.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtsqindjrh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtncfylxki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtwxaiqkdx.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtxoewwzxz.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtthkyugja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtzimqyqzj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtpbattgmj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtoifbkmak.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtsgejqqnw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtklhcferk.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtraebikes.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtlmbrcppf.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtjlcifamc.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gttbrvdpfs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtqiuiaovx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtlgjaezui.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtkhnpgsxi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtqlkrorbx.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtuhfmdqzd.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtyhxtkaap.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtlznaxmyo.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtwaocwdku.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtjuxcktbx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gthgkybhqf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtrspqckwa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtwxcgyeuq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtyfzdwc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtgoazpyni.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtzbzqvcsh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtomjaxsli.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gturwuewnf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvthhxvy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtaskcwvja.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtpkeelryl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gthgiohqsu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtujcgnscf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtrtjogcte.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtcagqbkfl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtdzyoxklt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmfyahhf.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtauhtzomi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gteoaiwyku.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtrfozlawv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtutosevrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtbdjxmxko.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gttskjevac.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtmdtsjtuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtudptcijk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtpwtxpibv.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdyqzwzxk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtggtbdwez.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtccqwjgzf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtrzinfzcb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtwswbazah.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gteindkyqr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtjnudskti.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtxhmnslrn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtjegbfxkl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtieygvxbu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtikjjtexd.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtcrtuuodi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gthpjqwvpb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtwhkezrbj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtsulzltbj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtoyrlwmqf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtliecsnwk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtvrcwvtel.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gttatrptda.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtcuywuvmi.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtgkwpqoub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtdztpbpgf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtaiybrgyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtmjntflqy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtlkzyatfv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtchwlzsfc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtgnggowmt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gthwrdqnhh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtlrstqrcf.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtpdkhfldc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtorwhwtap.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrurvabtd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmnsieckm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuuttbykr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtdvnuxxtd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtcqydfsjz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpkdwkkvu.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtukruwsyz.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtfkphnmgp.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjlygqxym.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkubrxqvp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgfimouce.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgksbwaii.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtatrgaatg.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnmajudrs.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjemqoozb.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtvkdlaihb.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtksgwztvh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtowwewxch.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtkauekqxo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtxwdngvga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoferkbt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtwcbxmfms.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtfbplylox.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtzoffowun.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtjmmklemc.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gthvgblyoi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gteujxcmgx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtnyqvwhro.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtzkkzvvwq.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtxlehgwuj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwtyyioa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtyzspeymr.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtototnlyj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtcafrsnms.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtxkvsnlfi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmcoednyz.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtswkyyrkp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtgwqwnnir.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtojwquckx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtgnfpwtmy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtvjezrjgu.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbmqxrrsa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtmuqqttuj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtpwtuidrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpbaqdxle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtyjlfdiux.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkcojexxh.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlrwkgcss.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gturgspodq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtirtidoce.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxbktuics.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbdhzkhcr.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtfqksulnh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtjxbnkyfh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtutafrdda.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtmttoejux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtshxmlpdy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtvtzkiisz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtuvhuvryw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtwbzclrpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtmpsprlus.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtlgmbxnmc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gthxqefmsk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtoewuujgl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtilvkunfr.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdnzxoph.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtrghsxpha.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtjrnsignk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoezjaku.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtyfbveqjg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbtghxdse.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtymhmixic.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfudwvctr.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtrkbypyqp.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtuccguylf.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtnapbhobk.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtdyumzezv.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtvyqbjcsn.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtquaqshdf.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gthygrbbir.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtelrbtbxz.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtzyvczzyf.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttdkjiyqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtqsxfxcps.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtyntbyjzi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtnvsamyqq.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtzumzxpte.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtfxlagjmu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtysgxrodn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtvjwfdesy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjghemvl.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtopiqecng.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtrjxniwii.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtnfhyxgmf.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gttxasybbz.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtalipavml.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtxhpzrkrp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtadesmziq.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtqkvknxou.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtynczntab.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtbtxwutje.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtrpdxmoqy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthoabzupa.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqjratfza.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdyqshwrh.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtujssjscf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtlpfavkox.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtqroliscy.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtdxykytdq.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtzkfbxfwu.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtzyhduebx.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtmxzxzwhi.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtdmpjslzh.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtluvkvcdz.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtibahsxkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtcobcujnc.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtwttbmolg.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtdbbfbzsk.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gttgfzfsui.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtufibruwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiuieeef.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gteoavefvb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtvyskgovz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtpanlqvlt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtkbfcmzta.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtidsdnskv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtlyaamzdb.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtrzvecfzr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtcoplktlh.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtpiquxedq.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtrqiijarp.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtoqktgreq.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtciyhojho.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtlmagokhz.html


<!-- 参考信息 -->