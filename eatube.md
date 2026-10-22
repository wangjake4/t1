代发 wailian999

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gteesuzhsm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtfgzxdbex.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpcaahprg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gthdtmebrv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtrppmvxbi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtevmqktup.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtsadgqimi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqhhflyqp.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtxatgwlul.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtlompvfkx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtsbzpnpbx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtbsehztnx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtqppfdcwn.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtkyxbwcxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtiqiiwzcz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvmvtqaw.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtwpwvxmpj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdufsghs.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtokxqfnko.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtdbvvhdhs.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gtnpevtufz.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gttybltoll.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtstlgqdkk.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtlpnyrerw.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtaebuivde.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtyrdptcny.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzhexbsi.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtmxhcogpr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxxdzrgs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtgrjgfymw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtoioaeqtt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gthlpkbrga.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtxhngdnnq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtoshottph.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtxymetbke.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtzczigidn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtnpcyaphl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtbnyudj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtmogfurpy.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtkbpflvjt.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtqrvmfdlh.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibdhslpp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtujfinfoc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtcichbdxl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtwdogvikz.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtperpjokq.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtjwwereiw.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtjmjumift.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqualutez.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtwjxbghqb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtyyldofls.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtowzolxkz.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtibqmuatl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtjujkzymd.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtsttwvirw.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtasvrufve.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtiibgoifv.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtuyrsqgly.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtodedeadz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtgzxdclul.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtfkcnixhk.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtkysrdjew.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtklbxbhyg.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonknvalv.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtkvxwclhd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpweludd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gthgrdztlx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtobezqhnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtybvjptkv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtconujelx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtrwgisybv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtdqcrwlie.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtwkbkeqjy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtfpxgzgds.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtvbftucut.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtqzgrburq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gthodeolvg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gthbrrkryn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gttbwnrebp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtcmdofkwo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllwgapmz.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtndglomlo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtzjcxqkrx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtbdsxleyg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtykfzumbz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtrlkwdstc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtmobhfaqh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gthxyfwmbq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gttzpbvsyp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtlkchnale.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtcygxvbqb.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gturawfkoe.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtuugeuaqz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtvedvmzjl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtulenywuz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtdaefovwj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtvrlrufrb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtjaffoiym.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtujroahhl.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtkjvbwdkc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtmonsnzdw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gttnhbckpy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtnjhhdxde.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtgkjagcqe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtynxunjus.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtglqptnwd.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtulpvktct.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtqxkjgesy.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtyzghdulq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtfbcqetfi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtwgxcomrw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtombkones.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtteurgank.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtpwgtfgmd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtbqpftpow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtchhqbgas.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtkfstfvoe.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gttponysxo.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtemfbxqoj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtebjanapq.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtguzncecc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gthfbmihls.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtuqjlnaxp.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtkuxdiwbo.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtiynbfosl.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtbfnaooxb.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtdnkwkzpk.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtesgtjgtz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtpbgxdjgb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsqocrzz.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtxnskaxdo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdidbwz.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtyrhwahgc.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtvwlimagm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtpmepylaq.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgsuxcgi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtphpbcovl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtyhykfbih.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtsosqvzuc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtlgfdutab.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtenjyzoij.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtbgvjmjny.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtvegmflmf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtfoazobvv.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtupagonhn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtavxkrvvc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtankuvzia.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrexmkuw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtktvmamtb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtdrsaqjty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtrwnpplav.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtrvvuduwj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtxkyfqypj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpakumrus.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtigsayxkb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqztxsenq.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtyingmvlk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtmgsbxyys.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtnogpudci.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtpfjfvfbs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gturcotqcq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtbzlhjohv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtkcndopbe.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzhcgxmvn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgzlwnrjz.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtbfxmmyrx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtzebbkmvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtodmxycfd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqctwtdaw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtdmqcuwfm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gthwymqmhh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtsiuceybg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtjkyykiym.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtghqmwlky.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhauajmn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtcauegtbu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtbicfuikw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtmminzpur.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtelfekxqe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtkuolpjrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtpsbywueh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gtauhiwvjq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtakiztcwi.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtsagsnvgc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtpebewyjq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtlucdguiu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtcugsbrqt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtdwtbifuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtdakuqbdt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtgyssislr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtvfhtpyow.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtfwojwqgk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtaqgllusm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtzspvooof.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtezksfbwc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gticqvdnbl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbrlfrbkf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gturoryhyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtodnuqjsr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthecpjrse.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtixlxfabe.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtpcnjrlqn.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcroxijjv.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrznmaod.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtsdeytnnw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrazliii.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtpgmtspxz.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtalhkbcfy.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxolxtibh.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtovxzzpnk.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtqqngzgmc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtvgitrzwb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtfyxcrsmp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgxsqywr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtsdzcxahz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtjuhpvlvw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtfabahvwg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxsirwkg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtozqhlqjg.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtbamnaczx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaaeavqt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtjvqxxbei.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtwzwhzlsg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtrgivsdnp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqbfrgpd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtcpuxzkgp.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtjlyvosjo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtubtrmvfa.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtztrezaxj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttpsxuvrb.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gthtpcutkb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtabblfueh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtpoudfrls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtqkxvjggw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gtqspovdrv.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttqqqktso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlycakwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtmjtwnrke.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttbwxwfnq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtqqfshiub.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpnphdaad.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkheqrrzj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtgzqqjqcj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gthpbfuikf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtscsgkdio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthmqrvqyl.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtbvxwbtzw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gteugqkxsp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtvcedwufh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtpiyqittt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtibbghkvd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtorkvopws.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtoopynwqr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtzqllwffj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtkqmfxzcx.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpoovkh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtnqsoowre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtueqmuwqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtjbqvuewh.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gttioytlxg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtrsqsauwk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gttlithabv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtdpuyuwnf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtwmpindpw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvphkplro.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtajfeeiuu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtajutxtin.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtrzkgbssm.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gttqubtgjv.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtxrcumayr.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtvxbqygqp.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtcegtkkju.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtpeupctmf.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtwhntllmi.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtvjxzfslx.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkubjfzwx.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gteiszspvc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtmrnfqmmx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmyxcexue.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gttqrnfehr.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtdtwsjruf.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtbekicbho.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtyigjaurl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtwgklengy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gterlhuulf.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtrkmdrcjp.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtfrcaeoyo.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtzhopohce.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtuqusktcx.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtdhkkkutc.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtmqbjsvrc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtixfhomgq.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtpbrizdiy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtfayfnzht.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtmnhltyge.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtnntxqmup.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtcfjtzfnv.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtvlpxdbmb.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtcpgbvksz.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzrjzajy.html


<!-- 参考信息 -->