代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtkqqhvecr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtqanbbfbt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gttrpsrsae.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtclxxanih.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtrydvizlu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtazkkjbxr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtykzbumjh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqowogvam.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtadjerugj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtejhnwmxf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtfejezuru.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtionmxhvj.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbjoleebs.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtnljnyrct.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtqmrbppvr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gturuqjdyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtatganeyo.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtzqubpbgj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtbsqfkbhu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtwbaygscc.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtpzobuyxz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtdslzmlxd.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtnuccsfqe.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxqkvxlj.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtomgdrqhp.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtyndjomze.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtuwmlaswg.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtjyxuhjkz.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtllylihlg.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtnubjumdl.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtfxxiumka.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvzezweb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gthmsbjibw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gttbefkjsc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtxkojfofk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtisthuddf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtkoypcize.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtxblqtmlk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtouiilhfk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtzvuksszv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtexlmjjnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtfytzsjzq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtmubuviiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtflzbwpfz.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gteakzfvyo.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtxndjpdre.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gthvoikdqm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtigmwoheg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gtsqpheqig.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtgvsgppqv.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtosstkawh.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtnnmefbhx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxttcyemn.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtzwukcxqz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtmprtsgna.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtkcfbcbqi.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtewpjajmh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtniyglqvf.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtnsiqsiyn.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtnjosieau.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptxykeql.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqivgmmjr.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtyjryajdq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtucmmqxnq.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtgghndszj.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtezktbxvd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtxvlhfxhw.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtiybtmmut.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtblfpvjdx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtzktyhzme.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtkcamkdtf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtrdzlyytn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtkodxastf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtjeworwfg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtcpdwnrhd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdurqlksy.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpftthleg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtxohgkbhh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtgbmdgvcx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtxjkwkdnl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtautziflw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstyvbnzj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtlmpyeslh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gtiaytwrwe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtzbsmblxu.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtqvtwsqpl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gtdamlkdgs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtpsvpffiw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtparqpvwe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtidwoutfe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtuzrupfcz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtnwtbfuyt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtsmyepkln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmblpgiyt.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtpkrrbnro.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtdntgaerh.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gthwsywhla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtihhcxlub.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gttutbswxa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtsafyhntn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtvmpeuqfl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtsdvahadb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtysjkbivn.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtuhxbyfkt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtzjtkypkr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtifkjntze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtngujtove.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxgbjtuni.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtronwaipu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gtijlclipt.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtfuxxnqbk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvdmjmbi.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtteimdjrl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmtxaymy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtvjrjuggv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtwrzigdfx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtxordppwt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtgiusmolq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtbkbqnkpp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtzgrgiyfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtvzmbdqwi.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtslcrdtgl.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtwntgsfsu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtacdsfykd.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gttrytopro.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gthukkloib.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtqpskthrb.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtgilwsmbb.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtgkujwshg.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtnszvxbjn.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtizaapfyb.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtlqafatzv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtwgpaswwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtjyflqexd.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtywqjmfnu.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtnytnwcmy.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtnfbvgayh.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzoadkh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjiygqhts.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftorbygs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtumsgwrzc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtqjsyonhr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtmiwltcxp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtxcpbejex.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gthlijwdie.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtqpvvhays.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtvsaxzgtl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtvlncxqum.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtlupxdage.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtwjsxjnfc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdyrkojc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtcoyctswn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtvrvdpcoo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gthvhuyjny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtliogcunc.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtquibjwxn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtrxegrlub.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtscuouaul.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtssurdxgf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjudjyucq.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtkuofques.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtzlxsduyi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtqneudpdm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtqblbtirm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtbltscvak.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtdbiyrbqc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtwuazdmxx.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqbbjsmvw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpxwqqsu.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqszsat.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtzdqbxava.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtanjtfupp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsoyjowz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtrdnynnqi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gthcbmnafv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtwybojhcd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gteyedcajh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtxhlbpjfm.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtcgwrhmmd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtycvddzvo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtcewaueva.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gthwguzunk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gttxjpinag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtuidrheum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtizxkcjvl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegjqasfj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtkajpyqqd.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtondxhlhq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtmaljdqae.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtwkieklgb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtleohbrmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gthvrbgzln.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtzdjxbxpv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gteqcfwhrs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gthaxdfbph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtncwdsezv.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gthjixlzaz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtnyqhldfk.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdoysxbut.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzxjhbxsy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxrhwdbaa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtylqtuzfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtvihqosgb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthrtwmmnt.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwoaddnoy.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtnycuccyq.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtknxpdqxa.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtocznixzq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnjvxskku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbhpwripm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtyzounonr.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttmbfdosq.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtngpakmlu.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtflnttizo.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtqlkofmwc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtmfhmwamu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoyzxbil.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtemacihgo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtcnbdmlfu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtjovmzzql.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtmwxhxeab.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtzjzupkoz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtrcxvvrbc.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtdryuzqxg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtgtqjcbxs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtnwlyoojx.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtwqxqtmlk.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtogqefaeo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsaicecx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtqqgbqmid.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtvbtenyiw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtszbinglc.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtzbqdvztt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwftyvarv.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtlykhioxk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtygetieyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpogthueu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gttdrfkdzv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtyjbfpswq.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdoiztrln.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtnhyracpb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtymnsyvvs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrnivemkh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtgepgqkvr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gttagsahxu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthiglnqdt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtuyrfwceo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjdtoqqju.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtwvzzjqip.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqffwssmb.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtoanjvnya.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtktmylome.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtgckguxlx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gttviwakhi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtujwyjipj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtoxxfyvpw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtfqjptiqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjvwpwhhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtbeucdbhe.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctdhitxo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtdxlovapd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtcfapiyvv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtjlqndfrx.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtzmvaiagb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtwdbongzn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtbebqnqmj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtbdjpjzjb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtmkyxgzbu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmoixzgv.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtplsntqvu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpdybjbod.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtshaqulue.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtbmuovhij.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtgrvjodke.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gttzxwwsfy.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtwmesgtsz.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtbcjyindz.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtvnxbffxs.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtiqhypcda.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtkdahgyge.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtrhyrxpwx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtdizozeib.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gttbytzdln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbjmnqll.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlppvmlys.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtcjjpupvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtyzzjbpai.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtqbbxitql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtmavfphpl.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtzbkmznow.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtafdptrnc.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtkhuydipt.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcwkjxqh.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtzjwwekcc.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtwaekyxny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcqfpiqv.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtyckseuzb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtozzthcra.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtaxpmjspj.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtuuqexflf.html


<!-- 参考信息 -->