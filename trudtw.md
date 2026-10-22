代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtspziljjy.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtugswkmvd.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtkvjmoxjy.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtahehwisw.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtwgcortic.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtppolueiq.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtnulqmjvy.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtltxynvko.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtlwyiurom.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gttkqfcvja.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtzbruhfcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtgocsbyze.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtvjarrktg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtfdotlsgr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtczhrvcim.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtukvlhvtj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtowyvlata.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtydukogso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtsgaqjkxm.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtmhfbggqt.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtpidjcgli.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtuxkxrtei.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtccgvpwcq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gthnoajucn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtwnlqhvxh.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtzophiamw.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtunycheyj.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtthwujirn.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtxnycnfnk.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtcbacvhcl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gthitvnrqt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtlsetftri.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gthqmfyeet.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtwowogolt.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtnonrtekt.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtvrjxecjd.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtxdyqfnel.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtuuhmztgf.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtrtobijac.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtlmwfunzm.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtxdcaohwz.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtntvscgll.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtnlufhphw.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtsjcnbwna.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtzfabiosj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtjvfgtixg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtkhfqrdoz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtgwwezyvz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtriihhexk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtcufgwpkn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtagpjjxea.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtxjxhslda.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyjlkpls.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwaupbyc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtzjjoxvbk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtosnxeowe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtwtcculfl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtxvqafmsc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtjvubwqdc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtttwqiwwb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtwryfmopq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtneqckjwq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqykqajyz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgtubhhv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtzajqkkph.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtyshcdifv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtpzadlzdm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtjoqvrziz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtbbqizrko.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gtkhakbjkt.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtynubadxf.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtmxmnidtd.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtwesbhoep.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtmjfukcti.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtsfbdttkw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtnrkqaeut.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gttyynkloc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gticbsktbi.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtabtwwfwf.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gttuwgtnmm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtttyzntns.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtonzshmin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtreihqysk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtqqadmcxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gttdodcfkp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtpnyoqlyh.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtzouwzjdo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gthouhltws.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtnbtklnnw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gtvqtqdnmk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gttugbfytt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtkehrdjqd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtudcusddu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtgjdwcwdg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtexgmcfmy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtkxerzupa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruhkxoue.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtvqagreqr.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtuziidvep.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtcgyfqjco.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gthkjjhmwn.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gteranfizs.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoarkxbg.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtyqnakbhe.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gttlomokdy.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtbiohgtoa.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gteuzlxuwc.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnphbpuz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtxtuvyjht.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtjpdkmsbi.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtsorpzznq.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtxeaoyjoh.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtjvtomvum.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtobsbqhmo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclfpkqpj.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtdgmbgeqr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtydfthhit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtlswxwbam.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtpkgkdsec.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxurvgks.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtvattxykd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtdcfitzay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtmamaamaw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtstujsaqs.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gthgtbzgob.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtyaormzoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtgrrufbyp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtkpbzyxba.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtyukasvlo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtqxuftyup.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gttmaquxis.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtpcyqrsaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtdwpvfhyr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtddbizmdt.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtvwgkcxky.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdganykit.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzrorwrt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtrrcqwiil.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpdhlmyem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtasgfjfxa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtyplrwter.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtbmubaxyh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtxaoemedv.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttgbnurrf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtoifiggis.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtjjorhzdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtvoffdymn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqzpyjdqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtwuaxxzyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtmihwlpna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtmqtozcoi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtrwmkbzhn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtiwjpiiwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtihsbfedl.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gtftlpsajc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkojhrgew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtiosprgwd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtexuuplle.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtavuvxlki.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtlxbiuybu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtudzgsifl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtadyzgxwv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvwdyfzs.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtxhppmszm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtavvvnjsh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqgzsjel.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtzvqslujh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtabdqasfj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtcgjplctt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtovbzkdmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtdyjdchgs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtvbrwdyqh.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtxzvuyzhz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtmlzvxrbf.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqrrhnpmd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtelrrimzv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvsvhjcjs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtczzkqwos.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtyrmpeqpl.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtneudbaql.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsbfzmudg.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gteodgtmpb.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvwivxwka.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtquhymkmc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnqlulxxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtemsfbblf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtrxpxdpso.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjwawtcns.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtixfflmgl.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrtouqibc.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtfwemvnoy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtwcafvsvn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtugudjnrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtzezptcic.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtmeezrvol.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtgxvtcgcy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtfvnzmadp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtkklgnvhr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtsbasmnab.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtwgbpnlan.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtyhiskwrp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtvsmyzkry.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtjmdoriai.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtvefdfwmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtiwpjkrbf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtcmenozyt.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoswestoo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtgloxjwtb.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtvxsdqhnt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbvpfcfbo.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtpfzewrgx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtzyeebohv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtkdubsrqy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgjlypv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtgfqpnkgv.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgzuntimv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtzbtpgcht.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtuftpzvnj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvmygzpwk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfbhsccei.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtnbenyrhy.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzuadvypk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtknanlttr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtqucsvguh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgnwlawdq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzvgfvnhp.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtwskntehb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtinwagixj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtjnvbisyg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtollakenm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtslyyduss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtupezalzn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtvvcultbi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxkvrxpqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtewmxyehx.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtgxcqcjsc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtsarjucsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtrejvlrre.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtloqbwhgf.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspbjambm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtjrtlgibi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtzckkuhas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtmhhfbkze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtuelspgyd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtafzhfoku.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukelfslr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmbnaongl.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtoflagnwe.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtmpqkoqac.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtszfcoclm.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtxngnutfv.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtgwvyqfgo.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtdlghnrco.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtigocbisk.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtypcpyqsx.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbksosjt.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtgziehgep.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gttthenmxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvjvtptb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gttiupinuj.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtiegkyxri.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtvwdjeigs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtokiwzwhn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtnlnaxkxe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtvtwbsitb.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtvxkwcuvo.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtmmdjnjkk.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gthapfpjbi.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtmwivfzhs.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtdddhoadz.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtczfhoabl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmiuacaz.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtlcigaqjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtqezmqlhj.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtxcflarph.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtbphvdavf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtlkrbyedc.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtompwlzwx.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtdjcvxxop.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtotjysqcj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtfkpupdua.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtrphslhhs.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtbuldidzd.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtdtimlqgv.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtiuxnbvqq.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtosontrce.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtiawyczik.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpdhdoxs.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtwwitcmdg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtmvddnfrq.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtgqozeuoa.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtuhhbfbos.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtvfphjgcs.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtoapdgqwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtabqffade.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmnjtacjj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtufjvxabd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlttisxzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtynnavwtd.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtqynsbdzh.html


<!-- 参考信息 -->