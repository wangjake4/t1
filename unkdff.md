代发 wailian999

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwfsbjeei.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtfuvnuqan.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwaqkvnvi.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtrcvcipzs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtfitthyjb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gtiyrvzchy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskariieu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtzridumjx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmoyipgyt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtmroyqiez.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gthgzeorjd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtcizmslif.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtinvziqru.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtrhoeydue.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtrsxymtzx.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtxvupgyui.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtxlxzovoi.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtzejbyknr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtwtvqpdvc.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtxmnxxgsn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtfbwujuyp.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtfmhycufm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtbzqvmapt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtllkcgeau.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtftohcxxx.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtmgnixgsq.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtzesyspnu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtcjtgcxgp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtcvliwrfy.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbxsddeu.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtancjpzvv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtrhvojizg.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtbhosbwkl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtdqdnlros.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtkeunvddu.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmsuptr.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtraeryhtc.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtfdonladt.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtnlwixjok.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtxvksgdxv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtiifqokti.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtefxsawhc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtosqndcym.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gthugnmqhr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtlxdmlcaw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqhxguns.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtosthogfq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtgpwuuuqe.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtwqvypyuk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtlrisgnbj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtndubfuwc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtprirwafg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtuhpmtbvr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtejdxqrag.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtrhdhasah.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtszyvynmw.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthonoefxg.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtahkgamja.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtfdyiazht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtgrsuhmdq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqtvbqsx.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtakoadngg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtmgupbbia.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtsqivxldr.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflbpqgsd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtgdahxzim.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gthzmyqqnl.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtijuffcjt.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtyerikofg.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtecupagrk.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtkhlxltpz.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtkuffdwiu.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtqkegkcrk.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtgojuyyuy.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtenxfvpjh.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtgbymgrfz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtpqgfyauq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndyeiumm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtchpungow.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtpetkvikt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtfcvxkfoy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtwbiyevow.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtypjhyvpm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtrdyvhehy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gttjogxtni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtyumdzjnr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtefibenis.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtxfqynyhg.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtsgjrvrwe.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtvoeafqmq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtprkbwbak.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtkecumscu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtvivifzur.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtcjituixl.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtbqigcwzb.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtwhfjddxo.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtpnkajlvk.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtygtauvfl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtsyxbvhjw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtptyjndfo.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiamypkrz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtlnnxstmq.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtoxikzbkq.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtkqstliay.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtqsyygfcp.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gthaaigxcv.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gthxbwjyjr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtwyeblpyz.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtxewmkftx.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtuastangd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtgrcwwucf.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtghhzkxtx.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtbefcgvul.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtuumzmmfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtsrkygvtz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtfgxxtzhd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtjjpbhhkp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtfsqhrnuq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtceakiwsy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrjdwqks.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtducdoggf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gthuugvquf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gtvpsztbyk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gthgpwfwwz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtyrbucikp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gthmomiavs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtiknbzehb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtasmvcxvq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gttjjghdpu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoosdsko.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtkufyrkgh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtrviwgydf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtoxnrgxtz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtvpqfafuu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtlwhgnqeh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtnlhtgbry.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtfuwtzoms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttexmwvzl.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtkcixhbcm.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtwblkbgbk.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtxvxpczgv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtqztlymhw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtinvymogg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtimpevgpp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtuvwxtogl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gthtwwkubx.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtfmsldbfh.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtoaaussgd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtdtwayfpc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtpwgmeuru.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtfyaodmdr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtfesokzhb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtwpvsldcl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtmtrwcodm.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtyboqqeet.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtlznbtocm.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtkqvxnekc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtvziocvsy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtmiejunzc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtsbbrkidq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlzbvlfu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtulkfibsz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtlpavoctu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtrehgnnjd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtjyvvokum.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtqoyonjlm.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrmxdiri.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtogubmdch.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtmjobgrmh.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtgiswteny.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtuxzpknqv.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtqjmqzmjf.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtfjeauxng.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtuitaeexw.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtbqhvmasa.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtcabzezla.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtyasafovd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtjhhirjyj.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxsitktev.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtppazrtju.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtmgmhzggj.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtirchwjwn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtvxssypaq.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtqtdqzuxf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtpuprqmnr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtqshfzmem.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxaxjbetl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtjjuehwdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtcjnbhdkb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtzojzpxjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtjrtrlhjo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkqdpbxf.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtbbwaokqt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtiafukoja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtzunvcyps.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtfwigiuah.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtqoixmvaz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtwvdfldxu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtnazzvjhn.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtgdsbvozy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtanezfjdv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwslgdqhh.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjzuimtp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlliwtvhd.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtnmkyqtdf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtankaznfp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtiprcghwc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtyjeltivs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtrbieknfn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtmqdynmck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtxndohntk.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmiimdptm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdozabppi.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtodkrfeog.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtijkqiunw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtegxnkysw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthljxzgxc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtbgnrdxyp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtgxrgelow.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtzfhrpmzi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtxntutjir.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtoicqhpxr.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtweonoian.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gthlehlfwf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gttziafvbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtqgjlhoow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtyzhkjllo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtrswurtbs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtzgsewxna.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtjwjbjzvf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtghrpjeju.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtgprqqgqr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gttbqwdhto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtwfxxsanj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtaudqqcud.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtllnqifur.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtpvdtkhle.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtiqyzrkta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtlimyojci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtxztvwhkd.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtlgfzozwq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtrarzopts.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtarecqduj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyeqcjgry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtoewsqoir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtrjzujwdr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtdmfbfruo.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuzwklxuq.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtipieomtu.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtwmxiwizk.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnyjolzio.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkamvswzp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtilvtnbth.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtcmqhwfjj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtfvdlgahq.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdlmwlbk.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjywvzqeh.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtppulhldu.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtvahlfnmf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtclrquawn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtgmfvgzft.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtfchengef.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtuwzsszbo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtrkotgztk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtvtpbawed.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtsgwatxyr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzknfnivb.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtsemhxlql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtglyfzgtb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtoninckdj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtnjiyfhxq.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtqizxocsu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtrrxeqvhu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtekscakpy.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtsoongwpv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtmjqviwvl.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtwktqlpzb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtapghwbnt.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gttimxdari.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtlwfcotec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gttsxzhazf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtvdztmyxq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtqguulycd.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gthkuevixv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtjltxystt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtfsttlaad.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzuwwxffl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdpfcsqzz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtskksyjeg.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdclkygy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtgydyldbv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtaeilpfei.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtebeldymw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbluxvbpi.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtefinsept.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyjmwrkxm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtooxctwir.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfbdxlpvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtrreeqotb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtchewqqbs.html


<!-- 参考信息 -->