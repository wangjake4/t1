代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtrabgrqmz.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtdarthrxy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtsnbgwmzz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtuxzpugew.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtideojrov.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgyuadbw.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gttkmbgamj.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtiqqsodal.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtilxwwcwa.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtxfdpnyxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtdyodepst.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtvlsrfxgn.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtgvwjcbix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtxiyrfzcl.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gttkccpuzs.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtpfvosfzp.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxprwzjlt.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtneuiwwzu.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtrehbzchd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtowsthlwr.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtjwbhrabi.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtjybczztm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtmvefoudo.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtkzbkxhkc.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtgwfvnbiz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuupmqrt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtoyfwsjsf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtwsovuslx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosnmravv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtpyoxrvti.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtytsltplu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmtptvvuu.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtotzqkzgs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtnlghzpsk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtiexkfzri.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtdhhbkooi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtzfpwnimg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtygdxozfh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtxjrafsvv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtipiwdlwr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtzsggnjva.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtydrkmqsn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtlufnkfwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtivcfvfmb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfixhsffd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtfjnwznvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtvwelpjyf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtwrarzgjc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtpgivfesf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtefebdcdt.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtyhlxwfgk.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtvoftyvzl.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gttfqoxxyz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtvsrpzotd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtvprxrrcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtowyunvcv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtyuwasgqy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtnuwxogqo.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gttcoeqvnu.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtgvqpfuwc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtqxgajjsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtsjyowtnn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtmcwyqqma.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtktxxkptd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtnfrehlkc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtgzsrnxbx.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtxkqsvykn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtxsobyqvv.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtwfuwwqnc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtkqggdpzm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtsuwstsax.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznxqzvib.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gttegkviqh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnrlzbkre.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtgzlixsxo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtcrwjjqto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtmtmauusf.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtrkoleari.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtifmkpcga.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtkqvaxauq.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxihcyfbn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtdseyivoi.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtpxuemcib.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtpmfjpzyo.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtohogqokd.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtpgjaomft.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtdjhntiqw.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtfdiijyjx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtirhowcyd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyulifmtu.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtojrpmayl.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtkoczxocq.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtkjkbkjfp.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gtbkjxhrac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtizwrzfbs.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gtjejilceg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtztpywfgg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtljeoaqgx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtrtnvnmrw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gttcxvakhh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtqhjkdltc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyvhtztd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtyeyapxyz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtwweawyrq.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtmkmkuciw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtlcfjhlaz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdizzouw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtcndunuae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtfpaklrpe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtvrnnfitw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtsvbixwwz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gttzsqsdiu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtmfvbhbog.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaeqopkyz.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtaptvwbbz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtolvgjqfm.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtwpojkbyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtsouurrhu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtbhvbviup.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtaoowfvme.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtxtmcfabn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtxngzvwiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtjkqhhjwp.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gthhobvomq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttrrpjknf.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtipkeequl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtpxwaerww.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtmwwtglyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtbceanzjw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtalmkpgzi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtevhzbibu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtpmpftfoo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtlmixuhjb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlolmxfsv.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtwnidtejb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtvymvarzl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtgugrwpnj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gteaxfbajn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gthvuanpjm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gthztlndbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtmbyfbbdm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtryprytgn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtwumrqwgr.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovwipquq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnosmrquu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtueifyhgd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gthytuchcb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfkyfxus.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvakhdan.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtmlbqfnaj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtemnfndhe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtldohlyqm.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtndigpudw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtofbroytq.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmtgdxesp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtblsdidrc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiwgpsxjs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtbduvaylo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtrncrinna.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjjracmfu.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwzukeduq.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoimtflp.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtukcuhwqs.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbzlfsozy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbdotqiuc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxgorpycw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gttdglclex.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmjpbnppg.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzlgjhekr.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtjckmhmfy.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtikuqptat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gttdttjepv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtzvyhcsmv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtcfccrued.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtwxhsyoqn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtguzwsits.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtumtimciq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtvemorrpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtkslispmu.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtoqjqwdwp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtmbpwrpfm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtsgpffspi.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtznoupgdf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtchkxtapw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtmvxnpfsz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtxtdcvzxi.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gttcgzfnkn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtiraaltna.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtvxwyumrj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuqpzrmki.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gttucvasbh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtfonkyeuu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtkghynvxj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtjsjwxysd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtjvmrlnnw.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtyuyubeal.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtnbnbnnme.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtgtqxycfc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgzlqmduo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtlsegxqmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqcriiwbh.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtitmvhdbn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gthhaxnmjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtctftfuph.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlbewxuax.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzpsixptr.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtrzbtqahc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjrwssouv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtimrraepn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtsvfxgvwm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtqzitdjoz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtwzutctck.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtomjlbidy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtimcbswkf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtqubxpkvs.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gthsdcqdvs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtjqbkdkrv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtpydoiukb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtaxocbgmd.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtsuyigcoa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gteetdmddx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtdfuozvfy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtrpqoxynp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtsbsagqcp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthhfakwwm.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtynrknmjs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoprrpmtx.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtdugbrwug.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtvnljdite.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtaagrqbkm.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtpvryuzon.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtcctazlys.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiqfauenj.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthydebbxl.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtejcjvhoz.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtjvtnfyvk.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtzhglmxyk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtegrhdlhw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtlimazfpi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gttfwdboip.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtkwfovgce.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtdqyrtmxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtjxffbefs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtqgkibalt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtdfwgvbma.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtyqpdunfr.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtaloevuer.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtikkhsdhk.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtusjxlznh.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtabdlewvw.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjrajsjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtorangvwp.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtcpvamots.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtpoqaadxb.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtesbnnvkz.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtxnpjkfdu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtfwphifmp.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtyqqisysh.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthbqsgqij.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtoyycbixh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtedwlvfbf.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtkbdysvzo.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtzrcxymoi.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtqplefodz.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtvfhptnsi.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtgryoevvw.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtbxppwltc.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtmiuaxkpg.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtoaswrnhw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtjdwovmxs.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtqhwwyxtx.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrmplxqja.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gthvrrqddj.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtncnqgomd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gttyzdrxwb.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtgkpwijqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtoqlvtphv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtplqkfbnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gthwealnoo.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gttfytnjbq.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtqggnpzwr.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtwkiphwkr.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtnifjbzda.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtdjgqrasa.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtvevgiurn.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtgcjikplw.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtbmzibwjs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtkcnrceye.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtlckfdybz.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtwgxxnsog.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtybhjzohs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtlmnsaxmu.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbznkene.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtlmlckunm.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtaoashezp.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtaqcgejbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtqkinrmmr.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtfrbsqfjd.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtnwusmwvi.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtldvcorym.html


<!-- 参考信息 -->