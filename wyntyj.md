代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtlgslojqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtswphkgxp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtzjdnocih.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtjkvznipk.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gtqtbzjjze.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtqrdthajb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtsybqnxpu.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtvxjsgpuo.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqsnadcj.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqqdoklvc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtkfpzlgaw.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtsraynypm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtwxrefeox.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtkgtzfgjr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtglpoavpe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtosdplrzw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtfyqrmjcb.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtrpxyxdzg.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtsqciavpe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gteebnmckr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtfquwzojz.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtlibaokly.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtgbuedemb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtrshxckal.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtdzaghmmk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gtsskqrujx.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtmvtajtds.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtbpwhsmcg.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gtcycuaxre.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gthhzydwlx.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gthlxdgitm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtldoufblw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtedprjeqi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gttnoittli.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtjvmrtmly.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtgzfxifzy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtgbrhhrts.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtamrhczaz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtfoxfeben.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtclhzanio.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtfguroxfq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtejugbtme.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtdjsrapdf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtnhexxvig.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtgspfwiug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtlcoknoqp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtzyfrosqi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gttcdxvqrs.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtercggvdw.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtqfceusjf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtlbuwcaul.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtroocruyb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtowoywups.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtlglmjtsj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtxsbmxlam.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtbxyzkqui.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtcfunhrzn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtndspkern.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gthjvcdoos.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtddbltioa.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtgymcgipz.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtyfujzwjb.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtwpswnrpa.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtmuklbgal.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtsbumnhpv.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtdhasobrn.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtkxjhmwvs.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtjcrljizo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtgigcwhne.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtodntcrxf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtfpedciga.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqibuzjbo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtknrlpkei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtnxgnejrm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtshmuhmyz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtphpysklp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlbydzuo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtokrjyoph.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gthejrhxtg.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtafigqxsq.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtzhwpimsx.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtfnvnmmnl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtxeardboj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtsmfswgmv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gtubjavqew.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtxakyxbtt.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtthyqbwvd.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtyduevict.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtxbjurgfu.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdofdvvdv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtzrdrfvgn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtlihatmec.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtqobqndlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtrgpovzuv.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnsrxgol.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtbmqxcnki.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtqpubzfmn.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtirgqwmcn.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtbydmarpz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtgqxwizof.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtglsexhek.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtzdxifcya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtkpmhxopl.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtffmvzwfk.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtmqhndsgo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtezgkbafg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtqxtjipry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtsuojlgrf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtlndycyhu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtfvjpwxaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtvuddrzyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtvoftcijd.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtxcwfffgx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtkoddrswx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtmxekmxzy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtajojhjbk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmbmekydd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtnaslcqhh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtsdxhxzmv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gttbooqglk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtnpcyiwoh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtacmoijdn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtctnwrlvh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtmovgmnng.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtomyjzfef.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtsktkbqln.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtswrwfoxy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtfsuzrujm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtdpzoemrm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtrjcrcdrz.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtocycmbia.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtwfbxnlsz.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtzttiqtxr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gttpipzwbm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gthedqzodq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtkusacqtw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtyditibfx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gttbkgppos.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtnkhdbbnv.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtbcyikgdw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtlxjlhzkj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtvgimyssp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhiyunir.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtsrncfvsa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gteoxqurxk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtkvlrmqtu.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzdivboq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtgfnowsuy.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtsuudvztb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtbxqmtdqh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtbabfgwyr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtouzezoph.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtbwujhmtc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtpvhgzhzv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtnqhxstmw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gthbbxbgun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtradaenxe.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtzfmvdqty.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtoujoglvo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtzfqzfyrx.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gthybuvvtc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtaudulenr.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtoiihawdi.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtbnvdapmc.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gttqqbanfm.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtbxtttjrv.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtgqnjzvxn.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtufsownun.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gttnqdhiwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtixripodj.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtsagcsvgj.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtelpqywah.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtotkwploj.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtjegdrltq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtpotexfrt.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtkoyhsvsa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtnmdlhzqb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtiadfuiyu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtyuwfkhdo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtjcklbayp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gthswwdqao.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtrlqcwfwv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtamtwfriu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzguxycb.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtawuikonr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtmgiiyozy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtbdkxiwka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtjdqybbrq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtbvvixttn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gteuelsosz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtpfjwtovn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtxjcvuemd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtwcbppbhv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlyptfzhd.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbzvaamd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnnktydao.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtnrhfzfmi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtimrissyg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtceoblstj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtxdigtufx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtbsezsdee.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtucxjjzcv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtvjmqalqm.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqofsvpja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtownpvpgj.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtyekexlbi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtycfhvcml.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtuatacpmv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gteomvmqlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtfxdhexyx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtttaxggja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtnlmvctde.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtzivvswxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtlkrtzfek.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtjxtnkdfr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gteiyaofcw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtzohocgzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtavqappmf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtjgkjrbqi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtegnuoxur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtcgbzeobz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtibqohved.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtnrduuvbf.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtvomctlpi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gttrohozui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtaxgpfjmv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtvmjzphux.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtqfvvmhdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtrpbtnqur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtludnmttd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gthkvcying.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtmpvcljih.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gttegyingi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtkzlzospc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtomaujmqd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgootsprh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlhnnucej.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtixvnufig.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtikhdaqgc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmsucfyj.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtputplacs.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtcpovsxwm.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvoolfapv.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjgpcrkam.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjqstajda.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtogqwosyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtbjpuzhov.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzlnnwoax.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpdtxkzko.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjernnrzn.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtduizysku.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjcigglu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtwwwhjnet.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtffofjtkf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gthtcrmhyc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtyqgkzsfv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtvhlklnrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gtjkcnprzv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtsrpsjovs.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtvrpukwad.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtaprykusu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtxjjoghfx.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtkxfwsoal.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtksblqmwk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtvdnjbcnf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtuadzktub.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtbbtfugji.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtzxaeghqm.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtslrnwtxx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmenzrxkm.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtlctlykmf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtenjjdgqz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfxgepdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqkmlsfvj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtwgkvnbyv.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtuxtgxdzb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtmygafgqf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtewsggahf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwsysufoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtfvkusgqd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxtmkjmmk.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtadmalesm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtqkiftsxs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtglziacss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gttciohijf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gttzjcnjcw.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtgjxllgsx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtcdeqrdkk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtijdsozhd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtilqwyjlc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdbhzdxxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtkvjotyxt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtgxdvjicv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtcvctatzl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtjjbouhlq.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtmurezvww.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gttgurjiyb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtswobsjip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtepwryftx.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gttgexuurk.html


<!-- 参考信息 -->