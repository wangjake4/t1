代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtsclktupw.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtpdxzmjva.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtsvydewmg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtleuzbhuf.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtfknprbiu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtkijqvlhi.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtkrfgpvgk.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtfqucjuwr.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtntanbyzc.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtbvmyoexe.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtyhlzeiqi.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtxlkckqrn.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtgircrshf.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtihnyobxv.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtxpgeiiou.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtqjipikab.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtebasrtws.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gterovnthx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtidbuqrty.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtfagniiej.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtenvsmcty.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtzyadvmpm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtrxotzcrf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtqszmsjaz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtsuxapauz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtzztphsza.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtfbfuogek.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtnruoooas.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtykuebhun.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gthpjopipe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtlzpmorkp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttirytbkk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtakrczthc.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gthsgcsbci.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtcsrgetcm.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtjkmyhapj.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtmzvpvlve.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtvfibqilp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gthhiuixbd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtyjaoawgp.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtipndxrkk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gthiqqmfbe.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtneldbhvn.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcftoats.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtmvfqqern.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtrmqabpmt.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtmevlztgq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtkiwvltqi.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtjrxnetez.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzillyns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtomgwfowd.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtstfowsyk.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtbjvnplnk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtornrnugw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtomnbwedb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtcrupkbrq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtqshujsth.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtsfeesyvx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gthgsxiqtq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtkyusxfto.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfzsvlgv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtxbtiaevw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtfxmorgns.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtsrxqszfy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleqqnatc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtzbnamdeh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtbsjdoaqp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtnchuzpma.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmarmdez.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtakxhxlfa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtkuwwkhwa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtdmrynypw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtpxhdseln.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtuqqobfpw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtcfxlctoz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gttdydlztd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtunxyhtpk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtrrqahpex.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtcnpeoxny.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtbxqjzyay.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtkwdzwusg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtusdvkudk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtwqrrzbkk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtlhhfjrjx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtxttrrppn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtwowsaxnu.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtghdzjzmc.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtdcklmoaw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtzrlalkbl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtksszpkma.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtynqeunmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtarmzigfr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtricstrbi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtkolzzprc.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtappwbfak.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtnzsrdhod.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtmhefphrb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtcscpiulr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcukmteti.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gthjvlitrr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gthljhjzso.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtiimairkc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtghekfhhp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gtrdxezthv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtkdaarhph.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtokmfhqrj.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtkjhqyndi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtisfqlqea.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtcnfdcsox.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtojydxoyy.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtwfnwgpte.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gthogzsuki.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonlhdlya.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtkvaoyyar.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtnnbfthex.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtbbckedok.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtvzzexree.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtdhllygwi.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtgavnxwhs.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtjupsfujq.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gtdocqalze.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtucimgqcd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqxjmazlc.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtphpadaqz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtgofnlvzx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtrogjsess.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtvcruzbcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtvrgxtlid.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtdywxngcn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtoskilqvb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtmsjlpmxq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkghvdby.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtrhpicgek.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtbtikxbwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtrnniixbb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtlsvhkcuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtdzalizyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtbrlygjyd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtyoiwssxw.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtobmihbwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtzipxkmjg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjtbligdo.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeagvgdj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrduopxug.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtoxqalpat.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtirmkjklx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtakqjeymm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtzfbxogbq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gttkvngceh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtsnrhdvcf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtymehoknp.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoluixpkq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtdoftgtcv.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtvbrlmdkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gthkqmtjfz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtvwojyzpl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtwhhmkhxq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtachnglch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtnarvskad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtohfwpwji.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtgbgeqhek.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtnhrvkydd.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtbonwvpgk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtkmfncgzg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhoroptx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtiygrphwx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetiorrhc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtggatcquq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtiqmqdtsg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gtvjvbqxma.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtsyjdhelo.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtzyrymtac.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtmwqysmbz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtfsbjpbwn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtsrtrmjmi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtffjeakbe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtkjnmwmvk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtnnocgeqk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtecjgvgrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gttycorpmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gttmgoaypn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtifqlbffi.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaieszmmn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvdjhyvsr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdfkbpxwg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtdgoiwokp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtebrsybwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtokwhtuea.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtogvdrpir.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtujkvuual.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfrxmfifr.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtavpunxmd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfroqdsme.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuaxtdfji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gttluinego.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiorhtlar.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmxmzbqwb.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqkelhftm.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtzausxtsw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlopkvnjg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtnmzeqroa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbazolph.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtmqaniovz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtjvrzqtrv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtxzowwlxu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtghinorbq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtcfjoxutx.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtacjvuqce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtogxyuqve.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtcjlmrjzf.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtvkyxpeqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtzkvnjjme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtnfuieaiw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtawayjoct.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtenguaqmz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtpkgpnqdk.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtwikigtvo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdygtldsf.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnxcbeyjd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtncxrwnjf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtexenqdcz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmoesgrgx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtvkefyiez.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxueiaraf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtavjudsbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtfsvkrrbc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgfjophbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtzrschmks.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtyxzkzelm.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcqtsyvgv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtxczvwfpo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtdgvbxqsx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtequotmro.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjccdujk.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtclmxfvfe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtyvrrmeya.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtjnwtahoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gthxlcyxtj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtygltakie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtwlbxoyln.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtlxryplpo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtssjmemfm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtksymfyfj.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtgzuokrcn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtjlobayal.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtilpuizeo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtnvddtjmm.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioscbedo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtuiuramlx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtyrrzauxc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtwfqkwots.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtmavwjzzg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfbwnfqgx.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtomhgisuw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttvuoxbtq.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtktscbghc.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtpcufgvbf.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwlplrkhg.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gttgaaenwt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtxfochwgy.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtikwgoryq.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtclfqmxjv.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gttthioabh.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtyxrvvthn.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtpgbwltds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtruradiuq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtgptldrcm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtgnhmioxh.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtvmfqabeh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnxxiapgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtaervknvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtztvxmaeh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtbueytgwi.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtzdikvlpj.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtznybfvvh.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gttyudqnvh.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtenvtazgi.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtkseafxgs.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtbhvcxcvz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gttcdyfebc.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtgywwggat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtkoialdkl.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtikdqpesl.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtzbfephua.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgzgvtgzh.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtqnuimzrn.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtkxzxoahc.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgoefsis.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwkkdqiz.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtmnwchypx.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtqkpxthry.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtejqxzfmx.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtdvfhwswy.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtuemogzev.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtafacnskk.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gttiarcofy.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtmedsxter.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtwfvxpjns.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtocufuzua.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyfykius.html


<!-- 参考信息 -->