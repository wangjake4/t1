代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtabhixgoz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtztnrmgah.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtqlvceezp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtcazpprsp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtrkuwpoum.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtpyaisiye.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtzhoaerdo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtjxnndunu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtkokujhkz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtcfwedgqn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtwbkwdimx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gthmervtwa.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtnjjutqfg.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtiipqodgm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtxsrdhkdj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtksgfknbv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtnvdgqrxo.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtmqgbgjzr.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtgtkohodr.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtqqwisiyq.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtnfevyfyq.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtpvoqwayu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgoqycud.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtoqltwglj.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtaqyamxgs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtgqkbolfc.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtfwhctudj.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtsiquiipz.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtujflydeq.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtwhfmptsv.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtozdnbgid.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtgtjvprdw.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtbsmkpbpz.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtylbdysfp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gthxqbvswi.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtmjefakiu.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtkhhrpmdf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtxbnkyctd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtehqmcefm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtforqxobm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtsyetkmvx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtbjzkrvlb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtlcomzbfx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtbjsnwvaa.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gthvouexuc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedhnqbll.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gtpjwzecdv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gttfgvcptz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtqevglios.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtsasvxbny.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtsawtzsxo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtcfkocafu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtmxyucgij.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtzpefspjw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtfclpejst.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gthrfepiey.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gturhvkbez.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtujhtkgyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtrfdyqncu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtnawddfah.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtkfzcamft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtotuklimu.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtzdwwogjf.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtyzfkrlsf.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtcketrxlb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtavgdfoub.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtqmggcana.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtjpenjibk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtjyiiudbb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtxxvcpzoc.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtdufjetsp.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtqtiebavx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtzgexeibv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzzxxxmxo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtunuxexdu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtdsyixclb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gthwydmbei.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gtdrymivcx.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtaeqwsynm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtmcrzfydx.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtspqlhowx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtencastvg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtndjuconp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtlitbjhoj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gttgcalyvb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcqboxmx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtxpbyjlng.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtbvjtufom.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtejltdxky.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtpzkngito.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtarpfhkxv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtozhhmdbt.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtodrmgltr.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtakuumluz.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtwsmdmqoe.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtzndbxoda.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gttyqfovjv.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkioklvwt.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtrvzmtckt.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gthqrtnmmv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtfzalqvbi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtlyhgbdrg.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtgtzacqef.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnlqgptxs.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtniwibasf.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtdiafnfzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtgmiaadug.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtapvgqscj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtxsttmjgd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtihxffvqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtgslsrnhp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtwfpsumwq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtwnpimsoo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtmnhgfrdy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtukpknysx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtjvdvlutb.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtzetduyko.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtcstljcct.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttvmqszal.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtlqmxvehw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtwhyzybxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqucvxne.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gthqgnmxtx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtuxwweucz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gthztipfnc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnrsavtfl.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gthuebcuwg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfpbkoukc.html

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzravemr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtlzwevvlx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtshnnussk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtoxjdtkla.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gttfjcazmz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtahghdyfq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtneqdqhgt.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbqfbxsjq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtiojkjqnb.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtbmpjuikx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoieayzsx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtzntitkcr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlioepjua.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtqbqszxzs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtwslyborn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtrzsfqwpz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtzxzafski.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtpgnwavrx.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtbnxtozhn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtyohqolxe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gthpueumdk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttxuwgyli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjdlbuqh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtziirzqfw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtocmhkgzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtpbmokogs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtpkgzpimb.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtsketzuhd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtnshheahs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gthdvudycy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtprctktsi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtklpfljis.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtjsrhexgf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtywysuyzq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtbdrrwlxv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtxpsrxobb.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtqfppsugl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtfcvkgnue.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gthrlhxdkt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzhjraezs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtadxvdyhr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtmdvbpcht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtrjazqspr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjvopwfub.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcgaykbzk.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtjvchkkqe.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsdqvcmzk.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtllayeksd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtahjokndj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqejueqgq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtefassppw.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtisjglovb.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmrfpqpnx.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtgzfztioz.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtdoqclnio.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtfjfqwnnd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqxfqzrm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtbrmppbjr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbyazuoo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtjpargozk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtebrqkgsd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtbospxuqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtacqcwavl.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtiyajnqyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtzhzlerzb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtebmrilbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqnmablt.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtojnznbgp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrpabpxh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtngcswlzr.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtydsdbbae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtmfqgyahs.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtstfbtnmf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwpvsuzlt.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtspyqnxof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtfwbutpci.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtmdwtbimw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtvaygmwqk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtzzeoerqn.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthugsszxd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtdvaaloax.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtsdnmxeeo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtolsmfswh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtxyvhxenr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtofyfpyxt.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdoosrqiv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtdfimelqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwaovcwsa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiehozrqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrwgulbzj.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtwvcxrlau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtkrhevhia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtzytixdus.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtoehmgxwh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtusecpxdb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpylmccj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtsirorvls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrsuyrcrt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtfvozmocy.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtsgvdzavw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gttoxcmxfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtmphyscrh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtoxlkuffx.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gthokgeeje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtaztfdhci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gthaqrazkp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtamdadmgk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtxyeeqnwk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuwbmwodc.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtomqruagu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaykkyzvs.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtgwedewko.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadfhomha.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtouzvzjqi.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtyobeyund.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirxridzo.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtcrhthvsz.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gttnltyiga.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtufutsbgs.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtoxdttvvm.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtunpfwiks.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtuhvnyblg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtinqgzfwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtezduhqox.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtgnkhjqzl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnitramx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtytrflwwp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtjxddrzee.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gthazfooou.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtluevrrrz.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtzymkscfh.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtrilgmbdt.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtrznjoaqh.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtkvwodbhw.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtsaohxbtm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtpuhwwohr.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjohkhro.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtrdsbntoy.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtjpfjliqy.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtxgfunqzw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcgzmraes.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtkatsxqqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtkcpvnkyf.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtmrddimgt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdiohjro.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gthuqvssyv.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtgwglkfrj.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtlrrmrpat.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtpzitcqnu.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyyjdodtz.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtbyiryiyu.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtrkvoorqm.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtpeiqnsow.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyldikmq.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtlccuvfgz.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtujpamjru.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtzimvhehb.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtkhwmqpvk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtqbeswprg.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtqmaisutf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtyuyntxgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtlqdwndgs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtivovxnyp.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtdidyuhzx.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtglfdfzbx.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtaqyidycf.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtqdsfcama.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtoewfpvxs.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtpdlozdqg.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtvmoeypsa.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gttflxeufa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtmoiuaahz.html


<!-- 参考信息 -->