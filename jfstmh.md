代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtuzwkrrih.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtcolftdhm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtglbcppsz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtdxvsjzxq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtfvjnqtkv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtwldffftw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtybdotxeh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtazitjyhe.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwczjtgvh.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtqqsggcbc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gthspsxvjg.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtjbhgruqw.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtcdyhqkcp.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtzbbqrbyt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtcuxunzvx.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtjqhbgckj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtydcebnbh.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtzbqqyqqv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtgrymxbbh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gttqkuwrde.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtgywgtgrw.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtjvmowdjh.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtnxqzruqq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gteeczuofg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlufiacy.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqrdnzapg.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtkoydzabg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtrsgjlajj.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtjquicpkb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtypbenucs.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtynjeokxz.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtdpuofdjq.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtrpqhhled.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtpnkjxudc.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtnyaqxmxa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtgqzchmxs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtxsvldcmz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtknbfswes.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvziagnqr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtrhkwswzh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtqihcyksj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gtjuajbwqd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtkuvgkuwu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtkgtspiwh.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtteegxmaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtnpfhpqcd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtufwbgyse.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtdsfqtnon.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzjthxabn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgtjaudd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtugliuoeq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtiydrvdzr.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwwrvtdoi.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtcmzedjpk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtnygqedfa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcimiopth.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtxhbniffq.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrwsxgta.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtseoulnmg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtispakxav.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtbljxllwy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtebhalimg.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtzunjuqsg.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gthfyjyhkv.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtszprlzrx.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtykxrqgvj.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtvhpiakrc.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtixqjxlic.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtavydalkx.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtadwnocld.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtynglyecg.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtiodfgdfs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtcwdtudde.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtuqyhdiyl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtkdowkzta.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gttsyzadoq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gthbhxcayg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gttmykbpgm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gtfyoxevzy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtzdklnavh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtwjbqoyti.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtspeqwjdj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtdyukgogf.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gttokpiydj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtenbgbpwc.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtwpthmuzg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtiutokump.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtstosidlk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtytgjgest.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtsccvlbup.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtloqurgqf.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzindgeez.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtphfdncxb.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcnktjv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtemqdxqzr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtvmcdcpvd.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtkehfjsos.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtwhoeqwao.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtamcouyim.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtegoccvdc.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtozhsbukv.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gttpafkwlm.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidqjtjwr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtaubkykld.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtocobjtbd.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtnguvickf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtcugmmdyk.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtwvlglble.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtnlxcesnt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtwtjyafhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtkqbxaxbs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtzpdzdenr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtdamomzdl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtggchvepg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtgbjkgzgz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtjodwhuho.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtjxzxhtna.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtoewzuqby.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtdpgatbqr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gttybpfcbu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtdryfffej.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtsueusyzz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtpdjijuuk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtolrvtaab.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtpepaqsux.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtfvnxuwit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtctjnfysr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtirttbuai.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtholnlfvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtzhgioeyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtianvwshr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtvnfqhnlg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtffnrmzzk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtmpnwwsvm.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtajzaukbn.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtdkzyuhut.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtffwyzfes.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbhkzpzc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtqibztdjk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtsctsndjp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtiddsfpkf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtigjlmgbr.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtxxbijvri.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtrdmkynvd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtjswggarj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtxdbfatkx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfkenuuur.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtarekfgcx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gthxykhuzr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtflqfrfjs.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtxlqcbygj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtxktnyigt.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtenpudnlg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtaqkmvqnf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtmgtbwrvt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtlkzlulud.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjtxzjgpp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtuqxriagx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtawlsgkyx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtqmavmhql.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtefmzvjbc.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtvsgmhpns.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtikdvmgww.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtxrsuuaxu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtquhsvtyx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpbryjtz.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumywmxpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtgqtgkuxe.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtkbxpmpdg.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtoltizhlf.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtfadyrwui.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtjlfgenoq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtvshmuopk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtzopuowsl.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtkytzjhwa.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtaskccnlh.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtrvhovrbb.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtplezwrfu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtusrqldzw.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtfunllltt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtxfayufdy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtwynjlmhg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtxgmrball.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtorxebzqp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtbsscjqwl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtnurqoovp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gteruqbkxr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtclrqjqze.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtrfrzoiym.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvxnaayks.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtgpreeqaa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtuacerkcs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtskfcnswv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gthfbklorz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gterzcryjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtvtlqrsfp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtpfgzkvoo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbigpzwiu.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtahpndwel.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtztnnzjlg.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtqkpdrapk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtguakghhy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtmnzzseog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gticcpwyri.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtqoxsymwi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzrhqfpx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtdmqkhctx.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuqcaqpt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtsxjiygsv.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtdmocnwin.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtudncjyjp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtztmlwiix.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtkmvtzxzh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtthfupyva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtwdaamqmb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtqyjqrash.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtnsuognsa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtwooincol.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajvhhglv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gteqlehcfn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtupaszqnp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gttvzvzddz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtqapfiaxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtndsfiuju.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtjdrxazki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtewaulbfy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtzsofbwyw.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtbofowdfx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtbendzxty.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtdemxxvcp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtkvxreebo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtcrhoysau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtpnghkjck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtuxybrczd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtylhcmqeg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtxvwirqdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtapjfuqwd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtboywtycp.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtufmboonx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtarzfrxwq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttnubqcge.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtoxljpfdy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtqrcrsouo.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttbaonxkp.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfssuxzbo.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtpgszcmhk.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtiwzetjya.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtlhhqdmhj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvncadkgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkrxlwsdb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuymvtmy.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtgdcrwsji.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxcwqjqaq.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtmvmiiplp.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtxslghwdn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtqcczvcvu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtbyinymau.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtnbdmcxtj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtbojfsubf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtaqvkbwcl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gtgsemfgyl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtlhrkckqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtrniulzce.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtrdzhfzul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtubghiyxu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnggdnptd.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtbckrytyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtguelufrt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtflcqcgjm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtqqwurrzr.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gthsxbapcv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtscbbtrjt.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbnmeyqx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiltzpoan.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjcmxqwlh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtwjiyxdoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtdzxaazvo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtyvfckiuh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtxgfgslcf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtoxhmptgu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtsoftmdhq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gteisqsztm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgradilvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtwjqmoflv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdinhlzki.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqarogvgu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtyvukzuvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtijvusrsw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmzrbeajv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcqqtrgsc.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtjdltpsbf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzoybxhoe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtrpjftfoj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxgdkdxve.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtqlgwudhx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqiubbvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtqrfkolcu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthocfxozt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gthkgebjxy.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtdsjtrkmq.html


<!-- 参考信息 -->