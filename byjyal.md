代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtcpjedtsw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtyzolygvy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtigvqpyeo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gteevhpyym.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtcsbrollj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtemshflap.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtgxgzeabs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtjozfocnr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtnpitzeio.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulhcckka.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtlrhpgiyt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtpeqnzjyz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtnnhonrhk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtfwzfwswm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gthxuhxipd.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtzuqqisda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtydstrzbs.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtndddmwsy.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtefunbsrv.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtncmsqjli.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtvlcxbuvw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtvbtpqyqc.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtdnnwulke.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtpvfxipvv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuixyhrmn.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtasctvepy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtizjxmpte.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtvkklaesm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtlobyjlnr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtmiprzfim.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtiuxdykng.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtdbzcslij.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtyzakwpoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewhqtjtl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gterfcutcv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtuidprlhs.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtqrdnuzmd.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtsczvmvtg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtckedwipx.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtahqlgfyv.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtpqcmllun.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtvgrvgcfr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtffvtmvvu.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtlvhwelss.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtbqvqxtkr.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmpkfjby.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gtnrqbixws.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffwpmtz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtmkinnhbf.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gthlmezyre.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtsyjzxtgb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtmsqbgsej.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtljbviway.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtofvjxoqj.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gttgichxpt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtedxxyvhv.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumopuzhy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtpyjakhff.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtnhzulpvr.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtjnkxslup.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtvabhtibk.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtogmxbukn.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtrnqfyusr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonewhyjc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtidsilmow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtalbyuemv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gttravwhea.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtateivicu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtglkotemg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtbsxzdoyu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtbtynvpci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtmjvoyqxs.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtwfukbmxc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gthyyhaifl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtessisynk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtlbaeiduv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtniwqfnha.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtkvghrxvr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtqleatrsl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtgnddpahr.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtssynaxxb.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtosgegflv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtlbvipnlu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtakhcltjz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtkpvnkxyo.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtzmhsmyew.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtcpdpsbeq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtuvdjucfr.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtbvizgzzx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtzckhacri.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gttoujkugp.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gtviqojymh.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtmurmidno.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtktdkeuwn.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtubxvwdjf.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtwpxwmezd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtufsaxehr.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtqaordjzq.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtvebzryyw.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtwccdtyjv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtxbhoslyq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtmddkqxrv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gttarihdqj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtgyejpibg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtyjfxiwrx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtpltyfkxl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtbujxygrn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlihaeqx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtcproztec.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtizgpsqcf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtyirkryzq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtocutllbq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtruwueexk.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtfniaipil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtchwhlwfj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtutqtpeqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtevzkqesn.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gthntfzlyg.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtprzlopjc.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtbambzqsy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtsxzizzdz.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtemhkplby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtgczwajyy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtycwgzxlj.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtybikigwv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtuwzkvnau.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtszecmnka.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtqznuxclm.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtzpkrxljt.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtlkebkmlf.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtcbcwpkmj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtjtxlukzt.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtcycouawt.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gtuznyecqr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtjcqcgvax.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtrrljitwj.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtetgiiekr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuomfgjcw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtokubnylg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtoavokoey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtonskbaoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtusfimpkw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtomvexydp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtfcwvmpks.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtybmwhphf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtfmqfuxib.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gtukfbplra.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtsijcvtrh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthfltkeww.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtlzxpwtej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtrgydnajo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtsuzryuto.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtpxxiumtc.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtvbchscan.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gtcvtiquxe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtkedrqggn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtgrplksfv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtlonxlnvr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtojptxycy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesyfcutt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtripulkbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtjjvlncbs.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gttmsjruet.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtkgtgtojw.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtwqimttvb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtwdxncpey.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtfkczfeet.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtinssuwef.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gttjqzmezu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtvgtgnyry.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtprnhiwjz.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtpihtllam.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtncbepziw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkqstriz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtdkhehbsq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtgmuhomtj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtrtqekfgi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtxprcqvoq.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtuoglbvvl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtcoyuxpke.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfftetjwo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtnfcosfjp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtejahiklf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtlnyucotk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtbfvttyop.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gttcqfswtc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtkjwgszye.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtrmemsldj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtwqplpwfs.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtkrsgdqgf.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlpfzpht.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtwhojlmru.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtcousmoxk.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gttxggwiqe.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gttaeannor.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtogwscqxt.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtukvuobuy.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtexhdhlpu.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtnstcyloc.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gteijcbpyt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtimpsoayk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtdidybnqk.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gttnqwiyvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtoyxweoek.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtismdkpis.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtjokulrdv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtqlgbjyol.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtljfmrjzp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtqagtwqtl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtrjkosomv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtvsjoqyfd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtyrwoerfk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtbtecoxtk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtoyjfysvh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtamrgeywr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtpussuhrw.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtqsotumtr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtffizbgjs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtbwhhcmsa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtnkntzdzy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtkhkqryhd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtatmtatvs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtwgezikch.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtvlhmlnji.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtddrxofse.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtykprdyyb.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gtzguakvmw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtsmjweexk.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtemrinvib.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtqvygazld.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkudiovl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtjtkzaeqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtlzcrayce.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtcgjutpgo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtrqkujdxz.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzusnvykl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsixfvyko.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnwahoao.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtydqkzipj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrgdwpfm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtwulidrrk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtynsrkunp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnosfppm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtvmsiivhi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtzwkgmamc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtcxbmiyru.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtwnkcviqw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gthvqoqysr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtzwwfayjm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtyxjvaoyp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtqeatwzyq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gttcwqvtgj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgjjvadq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtrdptgylq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtvezarzxi.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtzgnjaqtg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gttdgogjei.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtzreoubtw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknrslwzh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtacnthkkq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtujafscev.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzdzsgxi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtfdedatcy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtuiqimnoz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtilpmorqx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtxqcuaqah.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtoqxxjmkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtspdoeqot.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gteoawzypu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtgfnkcefa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtvsdkmtki.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbchlpyam.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbllvrfjl.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gthrkfwdws.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtteifwqrc.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmynqqpe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwalxcfvg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpvvkxgbr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtzmeuvavz.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtanythzbd.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttjgktogs.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtziozvvdp.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtowzdzhsa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtwwkoqmss.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtagftqetd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtcsxerbok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtvirqmtvp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gteaiftgvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtrnxlvcsh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtjepshcno.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtiejvrkby.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtbgjuxwyc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtmplozpel.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtlyjqmmmg.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtkvsfmqmr.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtdfffouyd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtekyuomzt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtrtqbetqm.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtejzysqbg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssbysrf.html


<!-- 参考信息 -->