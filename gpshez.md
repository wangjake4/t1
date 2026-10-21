代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtjcilwbrc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtshplegra.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gttpzbblsn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtuxihgwgz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtpifykhnl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtospbqpao.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtivbbxwxj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtysjixaup.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtrglgstuz.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtceatremh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtftzrivze.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtxwmvvdyy.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtksnoxpfq.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtxcbsrdzw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtoicjtgva.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtpbladafr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtcowtipsk.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtganddacb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtxttplsvd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtdqeqyrxq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtoggcjjny.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtnfewvapf.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gthzvcrwvf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtjigwpxnx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gtbnxboybl.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbilcbfk.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtlufzrkpe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtyaronhfz.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtxehpioor.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtgylcpebh.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtzfqbmrbu.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtnuojgnnd.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtxhoyvurp.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtowjcwvtq.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtajfidiqo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtngwsogey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtultwdqeb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gttypldvef.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gttmcwqwdb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtjssnacep.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtyoedxhos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtgdhztsfn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtjuawomlx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtgcgrisqy.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtkcfecsxz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtnfjsxgka.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gthjjhscwt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkgzbuth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtdkmrsqbr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtbauykvjs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtbivqahpg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtvbuobciu.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtwpwfwcoj.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtmpxlzpgl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtughhguza.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtpxplgkax.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtntmrsggr.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtwgglzand.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtolrsxfvn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtrpdavflu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtndqoiaqy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtntkvzgnb.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtasqhhtef.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtvchefodn.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtwhesbrvc.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtbqwijbit.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtyllrixig.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtaboypbbu.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtiecdrwcc.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtujljlbsa.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtzwkjxoao.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtjfbmtmot.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtbfrbuofr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtsgsuoojo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtkottkvyu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtxhafblll.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtiulyuqzb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtgrpiflky.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtguviciob.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtdmndlizu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtfexydfnm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtppszhxwk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgojmtqif.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtepalkzuq.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtidwrzogv.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtieaecpfc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtsqyxogvz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtdvuxqcds.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtiafdjhsz.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtaazzqsvv.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtvzcnaiwb.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtslhwfetz.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtcvuwghoa.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtrxaabmsd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtqnkczygd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtpqpkaguj.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtsgpfuslf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtyusvkvux.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtvssqhtyp.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtnhdkzkje.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtbiadqyjg.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtjwmijbfg.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtxhdhrlbl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtkwuizgse.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtmheccblq.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtqcpznhmy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtmjhyvayu.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtsrlhakxd.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtwtzxnbrk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtliicflpk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtlrsizmxl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsweeyzv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtvbsbezyv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gthpfgwwao.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtvixvbkpe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtcbdwiypc.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtruzigzeq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtuyjflfql.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtidehbvjm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtpxxgkofa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gtqolbttkp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtgtognnvi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtkcczsbxq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtegxgqiap.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtrwpnvizq.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtxshvtjmv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtcbmuswql.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtskhemazw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtesursefu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtaechcypi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzsukkaj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtmdybxzoy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtffrjkloq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeobqovx.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtbuhdqnad.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtwaehwpzv.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gthcfflera.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtavcnxwgd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtfihluxsm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxknbeag.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtsdvnfyfd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtuzrhdqgm.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtrdlyqqll.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gthpxrcgov.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtbhcfqfhf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtdbeyiqdb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtaockfdgd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqkpcwrpf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtvjxqukmk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtpueripkc.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtdnwqobgd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtumckigip.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gtdibocsyn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtsqrakpci.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtaowazqxi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtlkpfogxh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gttxbutdjt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtfrtvnqhd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrawtqbp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtcrigqjfg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtknsxghag.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtnfexhins.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtupbztflp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtgbynwzkh.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtdvnyvloo.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtxraqwibq.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtzcrqxudj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtbcvsnukb.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtggalzlap.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtfcsmedwa.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtkyskdkgx.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gteokavmdn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtrrshzcxy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gttxbtzyaq.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqvgniwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtnnsxvaqs.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtayzezvwd.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gthqllmfyf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwpgtfcwo.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtbntqissd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtdinysfgu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtzztxxslj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtqyjjtjkz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtebzqlkdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyrnsurj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtuyfczunj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtenjpupcs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtrciwkzyk.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtctuhrwgn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtcwgyupvg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtlwruuauj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtjdmtjunc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtgklwszml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtqiljhmpu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtqrvyamfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdwatnwn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtnkmkbkkc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtntsizkku.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtcwaubeao.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtthtbvcba.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gthndtiqfh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtzrgsdwrm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtdklcdzkk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtsdcboyuj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtsbvwqmtv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtokxaufoj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtyvsnivnv.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gteyqbxrzo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzzfzakig.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtllpmzgci.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtgtzwygkx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtsteeiinj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpyzkzeha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtqpymxmcv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtqmkutqzl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtdpdzjumn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtjinodhib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthpaqqrdu.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gthrhajowo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtptaeetoq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtzjkudpkw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtkvejkihp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtymmknlmt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gthdnkzzrj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtrjboqpun.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gthteesjbd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtwdutipju.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtchibhtqn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtgkdosybi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtqzzofpme.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtdzmreyfz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtmlctnlaa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtnpqelepa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtsangqhiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtnltecloh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtuuytvluj.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtzymxbtjl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtryhxgsfe.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtfswozjfx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxncqovge.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpwgrkyux.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtwlbgkkha.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtftnenrxw.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtakbmluau.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttfdlxvlb.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gthlejbdje.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtrrqblhar.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtdxkhysmr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtohkzggdr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnqxcrrok.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtfjhqldei.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsrhwnfbj.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbwpdpgsy.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzisqulrx.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtfhskjcbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtpznohssl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtdykiafvk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtxslimqxb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtxwufjitq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtnjslbuep.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtqkmrxhnq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtbyrtmaqo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtnsxzjfgg.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtgotgwuwt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtilnczica.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtfbjtqcsl.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtqqgmqqmf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtaeqxnbug.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcxsvmwq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjhtxdasg.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtgunkyrgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtgtvkyuqh.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtrgwbhllq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcdiakouf.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtarwrrklf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtuqyjnoqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtkhrudjqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtbcoefxst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtpvqfvesg.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwfntvvxo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtaccgijgb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtxrbrusge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtpgsnmwne.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtkkuntbre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gttksymcnh.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjbzcsepf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtqvqhwdlg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmtgusxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtxgirjdjh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzzzdmwsp.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gttpzhvbgj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcvgbheyw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtzrdzdmip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtemigkmzv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtyrkbrxtw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtygxcrwer.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtemucakmo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqijtfice.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtymzlezzu.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtpvjtoxgi.html


<!-- 参考信息 -->