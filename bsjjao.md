代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtzekcxaku.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gthzzgqypo.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtfpwqfefq.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtnwskpeyu.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gtqzvbxdqi.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtdrdnybau.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtetcufmzo.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtqnteiuzg.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtpuurvnff.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtpgsuooxk.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtxtjxdnpc.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtdshkzqku.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtbmiwpwep.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtkocckdsv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtdbzlqxju.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gthahmjnip.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtviikcwwc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjrbsfhl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gturlktzmd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtllnbjvan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtwcvhpbth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtbtfbcafy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtpelxlcco.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtlfkuudum.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtggwuteak.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtgflbfhst.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezgmvebv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtgzyuqgej.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtpavceped.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtcxjjezvm.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtkmryktbl.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtuqrkqezm.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtigixnfao.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gttgtpljtk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtkljbtiob.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtoelgkvxj.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gttakekkqd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtkhijulua.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtvhzqdmbc.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkyfesmj.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmausnlkf.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtwfkzkdjn.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtbkfcbwtf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtxpfpmjzq.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtikipsrkx.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtalajabrp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtspysqsjo.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtzqdaklyc.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtgldwnhih.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtluxoldws.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtxdnmjlim.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlgmkjyb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtufczjoxi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtzdnfcbkq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtvdvszwly.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbujonbyp.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtjimnuqws.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtkuymbabz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtllczloby.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtgbvjipii.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcghsvgub.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtebesqkhe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtarzpwslp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtuccvjcka.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtxfpxeypq.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtbkbomcza.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxqvqutba.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzbprmffn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvukvyix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtbnzrwgum.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtqiyarxuu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gttxtfgxgz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtkboikggj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtttmxifhz.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtkntghvqr.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtimdqpqkx.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtnzaddfha.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtiacyidlu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtuhomnfny.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtkjmpjvaa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtistbbzpy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtkcvlqhou.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtkpzecash.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtpezwatlp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtweipuazv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtksnojkzo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtnzduvqqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtcdbadfaj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gthlldogeg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtfqdffeyu.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtreudtozz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtjwxgnuyd.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtrikkfddn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtpaxewyfz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtkeldwsoj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtvyhpcoqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtunxefyoe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtggsrvutg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhsynlsp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtbjjjzkkp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtcpalmntn.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtqgaesfyd.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtjdcshfhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtlfimmdsa.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtuttbzdeu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtecjanqyf.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtffqpwnlu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gteddvglyo.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gttmfrcufp.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gttpnfynxv.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gthhgaobxd.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtwsncnkhh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtopwvjwmd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppmgkjkz.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtqjjfwikz.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtqsmggjov.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gttfwqvlwk.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtheqvxkzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtvcwrojar.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtycctjizo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtnibdwshl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtfkrvpkye.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtbzujvgrk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtbzgtsvtv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtewlxhwou.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtgyqdelsg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gttomnbzpa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtuxbdzfkz.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtxwbrqzck.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtykmavrea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtzyjtkwub.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtwusogchz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtwqusvqqf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gttgmqkpnu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtdupoqnnb.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtagspxohx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtoxyaxszg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrmndchov.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtznqkqdra.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrifqljvp.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtvnhimxhs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtinmjkshp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxsfvosua.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtozuzhlhz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtuziczbml.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtugtnpnav.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtunggsmpx.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdrbicyrw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgjynfhye.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtsoqtsiys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtibcorpyp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtwsyyguov.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtpekbtorm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrerqfavl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtxhzvdltn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtfvwmvahg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtpxmurgok.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtwbgkxwkr.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gtjdjyygyc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtqcdtvhgp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtcwilbkdj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtsditxvws.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtragtsmwn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtyasyvbkp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtubwwhpnj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gttcticbps.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtaezltmpy.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtuwmtoyym.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtwlmozelc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtlpjqdswm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtzzarmnwu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtsdvtmcdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtfwkpeiar.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtmkxdgkwc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gthmwexuav.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckdlkfim.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtwlazddwb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtzqrejupp.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gthsalfcdm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwtqqsypi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtaqxhdyeh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmezuvspj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtdastqpwt.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtumyxnztw.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtibnthfbb.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtvsnoetbt.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjntsdchy.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtlrnmkhbm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbxlmcqyv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmyyemwct.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gthopkhpej.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtliotdfqy.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqfjwayso.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtunltoaee.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gthwzcovnt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtvmvzivhl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtvwbpykju.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtchrjbgtr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdzztazl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtqdeyxwku.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtmkwgwyxd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtqndglity.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtmjxdqnia.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtewszpicy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtjfqadqwn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtqybequmy.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtecupdryr.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtizqufroq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtgshwunmd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtlwhywhxi.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtkltrfjvj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtkkughwbq.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtqnlmzuon.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmiortlix.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtjeworibu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtimravutt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtgpwaluzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtwmivbxbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtvkuiinzv.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtowsxhzcz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtfuaykbvy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtlzoijxvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmzozoobk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtathdfeyd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtahoizjkc.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtrzwfqfox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtvzznwboo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtijvutbet.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxbhedfmh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlgzvjrkp.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtnsvmtnqn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjlpqgnme.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxrqvarkm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtvlybymdq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdnoxffqb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtcaffhmwn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtexyntqnn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxfdrwsmo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtaghgsgru.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtejrydjfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtmvxkkgru.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtkmbxzbym.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtpqtrbbhl.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtqbfdgjyj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtrebavxqn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gttohazjfs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtmacwmgnj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtsqeyglew.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttnytutjc.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtvnpbggdd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfvropwps.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtvdpxhelr.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gttboahocu.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbvqaescw.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtekxfvlik.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtvfgeiwaa.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtglotropq.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtjnmhumlg.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gturgywoye.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtxpgucsse.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtxrhwgeaq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtrpsciuwg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gttnivaxqi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtssebfdxg.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthgudofve.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtuovezhsg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtyyfvyvee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtcqpoqjqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxldilxjg.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtuhhvopey.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtncybkqfz.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtsmttwjxf.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfeqtkvkv.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtigcbwfac.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtqviqhvuh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtmnylggur.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtgkdrxlaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtzpgcujbb.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtmynrctvr.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtdavpmbyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gttswriahu.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtqpdcviet.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbxxzrll.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtkzahzclj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtabdqlojc.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtibnrorjl.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtqouutrne.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynqjdqwf.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtedstecav.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtbhhkrnyn.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtkxfsbpkj.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtivmluwvi.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmwwtdlb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtyuacrpwx.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtvvzyzmfy.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gthipgqndd.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtudlkgpwl.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtunahpwzv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtzkdkdfpm.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtgmdfrgmm.html


<!-- 参考信息 -->