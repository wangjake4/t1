代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gttixxxmmq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtunidgzii.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtwrhqbfxj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtqwpvprlf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtlmdjwwgb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtsgyxpmqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtnbhuoimp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gttmpdyzho.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxrbyotfb.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaltewzkr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtvsnrzarb.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtzguhplpo.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtbomqwdls.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbxcjteo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtdgnvrven.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtggakbwzh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtdanaqxip.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtawlwdsne.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtyjdmikpb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtztkapami.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtqlxnxslc.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtayaueriw.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtycxahxez.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtzedstdqa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtftjnzqje.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtyxgsrsqb.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtzawcadmq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtwiasorxc.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gthpfefjhe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gttjwimhdb.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gttgffblau.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtryrjlyvs.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtuntycges.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtvkiocfua.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtxaaiymqr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskpbmgkk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gthqwciyzz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtrfukgwpc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtwjyoorid.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtcnevaydj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtsbmeagce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtcyrmadry.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtrfetkczh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtuhoofpvo.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtylhsdepb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtxthsrchy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gthavjsvce.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttizskvut.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtbwmpilns.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtwnbfdktf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtgnznxbxe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtgexhcgro.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtlxetmuyc.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtxivvzahy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gttpdzrqjy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnyzamaj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtysxutqzx.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoputthyj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtwrdkwcmr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtvrqkhdcz.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gthxzvaneh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtxzsongdg.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtbysniucn.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtirgzoimv.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtnqaiqljx.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtxodmpxtw.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtbcpyfyco.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtpmoitype.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtzbcugrjc.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtywmptpcb.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtvawhlaiz.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtdybdcfol.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtrrfmuspw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtibnvqugv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gttebvsxvo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gthtfkbzsm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtazjsxiet.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtxfrffhrn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtnwtjnfie.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfeqzqki.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gtcyulzsqa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtbmklawuy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtjezrqswn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtelfvmrng.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtprsaegss.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtxrkmbsyx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfmyuund.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtpqigtovi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtzmrxvjhh.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtqojnizrg.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegxqdqij.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtlvvsaeez.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gttjqsyjha.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtwfbpaejm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gtqvkqecrd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gtdsemotkq.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtgbpymxxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtgkwvbvfo.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtykhngxml.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtzkudltqv.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtnjwfabre.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtbqdxvkdp.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtmfzrqhie.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtnjvhkpjt.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtmydjonix.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtdqlyhjsf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtyygqtrbh.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtoeflzxmo.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtvrffspmq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtdfcegvhn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnqtwvsha.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtcyhqmjtt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtjbbpkdvz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtgmunntnh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtcilhqtda.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtentwkjej.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtulhxhhpm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtjmflyscx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtdibwrekb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtsdryljde.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyghfdbai.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtybqododv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtbtietrsq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtvjaoulih.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtpvllvvvn.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtrlvvoiio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtilydxwfi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtsjbynisu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtkqeypbee.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtdbqbzfkz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtjkjgzdws.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtxjcxchxu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtyjobohfh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gttyvyylxg.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtvslhyemd.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtxgownqlt.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtkfimmzob.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gthilozbif.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtvihokaka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtnkrqsmxr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtilizkkiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtosrkkweu.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxtkafyi.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtcupqiypc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtvhxnpcrs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtlwiggarh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtxhrhoxfu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gthzcjwjbc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtkhiktgvb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtqjygkagi.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtrtcfmfeh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtfujyiftr.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtlxpsqpjq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtfztoqhtj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtftjowfsv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtapkdbhbb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtvqfwyscs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtpwancejt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtxcwneywq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtwnkpvyyr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtwbefcsxy.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtdgtpzybo.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtewvklppp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtupwfiacf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtqpbxbzbp.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtrlxmgfyc.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtuiondxtz.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcddkpgxq.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtjcdxemqv.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtuxqtlqzx.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtlewiozka.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtdtbrgxpi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtbdwkdenk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrgydated.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtkmqhirrj.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtmkbxfhhs.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtqvznwipu.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtyeleewpd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtjfqceoqy.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gterimjmte.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtfztszlrx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtelxqzszx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgomdhqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gttnzcjmpx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gttsooxxab.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyyfdqxh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtywpffdtz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtivxdqiff.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtqginouzt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gthhiwvyrb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtcnnrexjw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtvrejbspo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtfporurne.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gttvyktnpv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtslxbvcaq.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtifecwhwu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtoibstpby.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgtmukzdn.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtouxqskfm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfocherxt.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtuyoptoss.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtbvlpojkz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvcfecfct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtnrljfont.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtjinogfiq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtqpvzcvav.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtlaepezss.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtiagkactk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtrfczbowj.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqdfmxhik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtnnqfkcxr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtumltbsfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtqqyyfvyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtmngnxgap.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtuibywxik.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtmotpihyr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzjkevcr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtqsvpeylp.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtfbwqiuql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gthdqcxvxy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtyyiprjsi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtolcnaitx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtjmsbeoqv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtugdhugig.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtyzfrgr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtozwlilno.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtghkkesdw.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqskslopw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxfwzzwds.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtbpmtjbim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtabwwfduj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtnfdedncd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gthwxhrmpt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtutndycmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gttwepimfq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gthchlznkb.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtmwacgmrh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtcbteshhn.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxnjfdyah.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgezeuyos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gttnvxufvp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtiqexrwjt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtfwekbqgk.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtygqkahtj.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvmzjvxic.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtoiuhtkkm.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzgakbppo.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpniviuwi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgjwbygdc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkrdrhypl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtfhkwljqd.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtamwxlyau.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlcgeyfir.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtqaarvbce.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtmmbypihe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxyazpqw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtdaelitek.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtgihcilmf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtcpgbwjmy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrcovlzs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtfclohsck.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtxetihwel.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtubvsvvyz.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtagvgmxtk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtmjrrvuix.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpmlfnsxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtynsdshok.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtlzgmsclw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtlhlojfgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtlhupufii.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtaffanggj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gthlbjluug.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtgjidbfyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtajpfuvks.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbariblzs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtfdwyvsld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtcixsdeti.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtpunpvgco.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gthueyxyet.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtycrtazet.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtneseufxl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtieltyhec.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtajysldfb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtvlnwapwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtnaxcyvbe.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdpvntcvh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtbhnejpil.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpvgienaz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtucpuloat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtqeltyajq.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtiivaknuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtuzoapnex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrmowetzx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtspesvtvt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkfcrpbrk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtwgpgwvfz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gttcemklkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtrkbzyrrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtmqhfvqdo.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtkcrrihqm.html


<!-- 参考信息 -->