代发 wailian999

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtxkkebxav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gteeorbume.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtwgjldmgq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtlywjubjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gthltukxyd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtcmntzpag.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtyxduqlmq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtdukahjlk.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtcfwcomsz.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtjbalauzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtjkpqwmbn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtouvomqll.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejpeifze.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtsdowhfop.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtayolypof.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtktpbihst.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtrybozzku.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtslddcotr.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtxchxjcdi.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtleyoepaj.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtabkqtolv.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gttukiyjlq.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtdkowzmlq.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljcgzdzv.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtdvdwjyvk.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttldxftdh.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtesppuhfu.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtftufxzjl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gttgoqreqt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtkcpbrbpj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gttmpocsrm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtififjtzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gticqkmqmi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtkiprifvi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtlsjhrksi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtbjksguny.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtvmndkzjh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtsedmjnmq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtfolgkauy.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtwpziocim.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtlxcldeqb.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtlusqlmnb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtwgbfdqzr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuckchlb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtndiumcun.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gteyvvmzzk.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtehpsxgzs.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gttgijggzc.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtfyzquaal.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtzxcyvfcu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtspnkwzpx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtwesdfdap.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtyhocuafi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtpcxzoito.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtpmaailah.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtoyllodfw.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtvddohaiz.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtxjjgpvyj.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtbnagypgw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gteoygsfmj.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtqrsemmzb.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtxvvwqrgs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtiyikvyrz.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtidvbqgmf.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtydczeodv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gttanmicsa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtwpqoqkwr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtdqxwmzcu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtdcgeghet.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtxvygvnhs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtuwxrrfpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxulzovll.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gthagqtsdr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gteqinegsk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtdtwnzpli.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunuqmfin.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepmtgnuv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtrulqhyix.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gttizlfxja.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtbbecfjro.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtuxmidqjm.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtemfxpzcg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcewgjdao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtsrmnpift.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtdxznubln.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtzvuwrwui.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gtnoezfvvf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtowjjpbsg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtroxhrboq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtabpluafv.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtalykywtv.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtjtijxccd.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtarprlgax.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtweznazkl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtbctgxcji.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtmwlwakgj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtxvjqlbfw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtqhnmnaxp.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gthrkdvppl.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtsazlfstd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gtszurubbp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtxembubpz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtlliasmnn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtgrtkfvjy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqnguhej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gttzgobavy.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtasxrkfns.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtfyyhhtve.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtyxhgxgtu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtramanedj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtikopbjhq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtsothyvwz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gteqmvglrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtfpjaewvx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gtikouiqya.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtkqmsgeui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtcgrvodbc.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtieoxjdfc.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtvdgrgwyn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtaqvcczku.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtgwcdxjns.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtqcckheoc.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtgwjxxzbs.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtpqlwjzie.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gthcyghiub.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtpvyrlprr.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtjckubujj.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtssveopmy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtjzxxozgq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpgbmjgat.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtphslgkvx.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtujqdhqrl.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtgxekzlhq.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtficcmiwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtrcnupbwx.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtzeratfsl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeqouwyy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtpomhbsuy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtgtbkmhdc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtxvesyunz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtjizpqhpn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtlhcfkvsj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gthgvyzsfz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtrjcuxdgp.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtbufoyxnt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuxtjckuw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtwpckdcpu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtpagwpgvq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtoekrtpab.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtycbjizyj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtsfqepktu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufznvzhg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtwtutbzim.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzinived.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtqbhorysg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfjqbbmpo.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtcrevfjqv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gthonbonpx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtibrapjwu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtpuipanas.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtnljqbgjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtrtgvecrd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtkgxpssra.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbfaurgid.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtbreyrehh.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtthfhmzrh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtfhkdkzxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtdncokkzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtekskffok.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtexclgamw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtntoypvdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtxobfzrej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtmnanccae.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtsslpozum.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtpogvvsgg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtjgondlox.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gthqzgxxxx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzytlqkz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtsgcyucld.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtnguuolnx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnpltirj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtpojcqfdn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gtwzchlbsu.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtubdchjci.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtponzcagp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtexmuwffa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtwuylxgba.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtfhrtkyed.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtdtgoymgf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtebwbqvbz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtlamqetci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtaogzppmu.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtpjpeqyzm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtqxzwceas.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gticsvaelp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlpefdbsc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpvpgxvar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtxqpabvcd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gtjkmlghnk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxefbqewt.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtoczbsacs.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdealutog.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjijspds.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtldtjpmdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtiezlllbf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjnuwbfdn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtmbfkdgpv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjklsnswn.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtymagljpg.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtkplfwxty.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtnbtzpwsj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtiqspccdn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtoekvlsae.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtjtfinzvt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtjpeaswlm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtnvrgambl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtsxdddkmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtuuxpxsxa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtfpvrgden.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtksiqrhiv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtdmjabjne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtjnxqtire.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtyeqdsfmg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtavacwquj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtmwnhxocd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtrpfrjowa.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtwknzzkga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtfpztotij.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtusihoaqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtevjehmzo.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gteqxstwzh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtseaiplcj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtcmraktau.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtudpblxcf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtcgnlssko.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdastjkjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtvryvygry.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtelskedcs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjlgdkgew.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvgljzihl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmliyelqo.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtholsgxrx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtyolgqbnb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtersuosut.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwcodyfhn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvzguigby.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtznrzkmyt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkrkhwkrf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtqynbjktu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfqvecsza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgzjcafuf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gthawyynsh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtkcyakhib.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtuimumaro.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtzdvcwelk.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtublcctql.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gttbbnhjwk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gttxvzasun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtklrkaxyq.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaenwerxo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtydhbpueh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtseiffhnh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtuqojsqqd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfpwddti.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtocpgkzrv.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtspajugyn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtifkdgmxx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtdycxudcx.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtgyvseaey.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtonbbgklr.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtfyampnjo.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcpgxqbxr.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtghkvituz.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtdqznybeg.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtizyurejm.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtcakdncdk.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtzlosypar.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtfmeboshz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtzopcjoqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqazduocu.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtijfmbqfh.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtcwkkbdmx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtvhbswrlz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnumudacg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gttlmogyuk.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtzgqkgogj.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtpyqfxizz.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtmcssfxdf.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtmgwrkvfs.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqrwlejcb.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtnurxdkjd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtvoobstno.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtcopedfif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtxefwnmjx.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtjlpstzkn.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtckmnaqtm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gthjtrqkbl.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtaezottar.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtdbnrhydo.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtuvkzwpzu.html


<!-- 参考信息 -->