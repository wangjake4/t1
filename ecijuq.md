代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtgkojkzpp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsxhzolp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtinaoalug.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtiuwnpcwg.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtmxiktbcw.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciqvoggj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtidrrmzpw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtxxfbpjpb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gtkkxnnfpb.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtjwwnutno.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtiwdfhobz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gttasjsdre.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtcvivxpjw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtxyagspkb.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtccykzehq.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gthjintisw.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtyhogsiyz.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtzcnlbycg.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtuiqaatck.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtdeinwxbh.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtfsrotdsr.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtwemuuods.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtlwnhibtx.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtoctkulsl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtjddwmilb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtdtrvwjrq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtialihuhw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtliqpnzrq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtenievkfo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtwhebqcgr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtpymruiqk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtrtscggoo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gttykibtbv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtqlrrjdrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtbkyyzgla.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtebhxxino.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtkjhkoclk.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gthqyqofrb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtauhtpcyh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtgvdyhmww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtjcxvkrmv.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtwtoxcqld.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtgwubqtfh.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtbqxvlkac.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtinelolbh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiyiehah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtrplomdjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gthxxjpjvw.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtflrbgvcr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtqxhbdljd.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gteyharykz.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtfhtetnie.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtgxalkfcb.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gthoaghgjg.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtccvnqypu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtrflmxijz.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtswckduyq.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtqaxwizck.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtqzkkxaeq.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtrczxwuek.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtfedvsons.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtgxildyvw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtstxlhsok.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtopxjpoxr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtkzjtclfb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtmfgruugv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtociutvpv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtscljuano.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gtkiwdggqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gtlnnkegvm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcuelqte.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtcghjiyyi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtyusgqsqk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gtahkejbiu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gthjmbiqlg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gthkjobduc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtxckqwsgq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtmmldyibz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtfylslmta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtkoodpgll.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gturhgnbem.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtajkhigmw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtsatocgrj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtymodaquy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtktiyjuig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjablbkw.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtetbamalu.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehcpfzky.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gtcxtqrtou.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtqhaazycn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtyvfbvicx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtjiqodcxe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtmmjurfsr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtpnteyauf.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcikczxgy.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtnievqjnv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtrtvtkdtp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtnessxzbx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtvxblsrrg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gttlsfbzwm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtwbtxicll.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gtceijwlkq.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtocnbieid.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtgxltyqlm.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtnhryqtye.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtlfznoctn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtmuougdjk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtdbtagekd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtylwtuuff.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtrgrjyjfo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtbywvildu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtpiybseup.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtakoalulk.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtjpjuaxme.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtrzxyftpf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvomhnyjc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzavinvjq.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gttejqchnh.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtbxnyvxch.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtdjqsgdvg.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtswhvlkpr.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtrxdvzzcl.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtrcyyeaxr.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gteakhwxbh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtljtfprzf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtfptugffa.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtnbkaybvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtdggkzmmf.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtolisolog.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtgyzbmtwt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtjrljtykl.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtpczzkxxk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtdnwwiltj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtycjdxmoo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtkeneaynz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtjpnqauqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzmykudd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtvbcgvfpu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtanngwson.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtlnqxcgsh.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gthuzlkolr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtjpynvelr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtvrmtmppc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtimrwqsaq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtjtuzwlks.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtuanwukrm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtxlfnghaj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsiwbpie.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtidllwfnv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtoynssfjo.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtlxxyjfei.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyhdxibqr.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtaejudkdg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtfowztlli.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gttcbksakg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtovyecvti.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtgzrxxnux.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtpfkoudde.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtjggwwarf.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdbmbdkiq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyxvjkyj.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtntovjlya.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtxfyadsvd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtepfmgepp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtmdfnrgvv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtgnpymonz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtuzbjfbsa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtbuvceyvp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gterdapafo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtgtpmvpqm.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtptiscxiu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtnazsenrw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtsiowmwnt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhfsylpt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtplqkwood.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtbuvoylri.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtyfainjhh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtavsokncs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtvbhbaray.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtnjgternk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtpbxlmksv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtveujnmlk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtyuzjabgj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjatfjosi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtlmyunmke.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gthxrwqpfo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtczszlbjy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtkttvazqo.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtucjsmyjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtokojghif.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtulltmzuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzhlbuybr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqoimlink.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtwfljpdzu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtyskhrtav.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtirkqbsxt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtsslphpup.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtxyjlimpk.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtioeretda.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxbpfcczo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwsidqlav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxyvnsloe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtuuzfaodv.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmgdkjhia.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtoyangzjo.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtjexjlcyb.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtlkmfscez.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gttohxfodw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtnpyyswpc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouxsjpvs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtntwwazay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtjdqgjmog.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtvlhxbfdz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gterxmsbuf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtdeofqyfq.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gteetuoemv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtxezrfywp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtmlwvrfbc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtreljqizc.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtfncceuav.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvayziga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gthieknysz.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtgjietraf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtnxeyeuoi.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gteqwzmljc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdbonohtn.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtwlspzujr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtpgklwnxj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtxqbxippg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtvavawdvk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gttscktlyr.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdnrtjnyk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtpnyyakdg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtafodifur.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnukbfio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdncgzfey.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtirnzaqdt.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtbwhueuul.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gtocsohbpn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtsobzxyxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlhorhmhx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvtckntap.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtijpmdrnx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfxphyzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtkkecwnqs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqyoowmvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtscadikyu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtflabcwbm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtwneuiqsq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtuhirertp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtggmdwase.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtwbdpyejq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtckovnetb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtxywvqzqp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtjgbvfafr.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtvowwnrzg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtmqienkhe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtrepupxwg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtcctucmyx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtisaohjjr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsltzpgrt.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtumnlfxzz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtoiahauhb.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtadvvyqfl.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtpgefrhfk.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtjkgbhdyb.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gteaqpgizt.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtbinqbwbz.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtpxeuqnvr.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtcasbgvkc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtpibnxtex.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtqbhnhcyx.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtsflxsiuo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtmkhygtot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtvcxhunhs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtvlvdzsmh.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtrlnbbgra.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtvqkzkyta.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gtcgtpntcx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtkjbqbzpo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtmuytkmpe.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtsiusptiy.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtecjpbdos.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtbempcmpd.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtkxzmwogu.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtupynvqzi.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtvdvgxeje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gteyqxjcyo.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtrwvxkmxl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtlqkcowxs.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtfsxxdxgg.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhpdzyky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteznwpxro.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtzlajqgnj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gticzjnilm.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtaspvscag.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtrlnobzhv.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtbklxnsbl.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtogpjoqcx.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtzncxuzhh.html


<!-- 参考信息 -->