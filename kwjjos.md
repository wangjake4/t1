代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtmwgjzbjf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtmatdzdzi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtccdahemp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtcqfapakv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtcuwawffr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtzcziwbqq.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtgaxcjtrh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtxwqczifq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gthgyzsayr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtoncbphqp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtxswcybio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtkuhvqvso.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtoxpznkwb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtruuasgei.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtrcfotgwh.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtmoabqiik.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtarjpwhry.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtjivplckw.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtfzshsibi.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtmdzrobac.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtnqubghiu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtpefxkgst.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtacwlnqba.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtrhijbpuy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfdvtxstg.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtiwnnqglf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtssrprgtg.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtsbmignxh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtoszdclpz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqukteav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbbnencs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtbibrjfdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtdkufsiyk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxxizojp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtqgftjhrg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtimmkkapk.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gthrjjuqdm.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtnguekczx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtzfzpzkyx.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwmpkzjw.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtgsviulss.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtjyhxyiml.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtkgdjxxyw.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfcbxezu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtvxybpyji.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gttnoxyzrv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gtnaqloqca.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtwuggjaik.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtwixvcfaa.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtflymsuia.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxgyogvs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtpfecsdnn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvsurzbk.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtfmqdqylk.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtnkkbyyxo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtxlitnltt.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtlyeujtmc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtzmxnaqda.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtbqqzsoyz.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gteojzdynh.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtfairpngc.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtsgphehem.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtyfcluxgi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtzpmorobs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtycasikdv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtlxnezwmp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtgstwhebd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtwxkaniee.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtksmhtpvv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gturtoulxr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtlwphqllr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtdwoxlijh.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtkmgxoekf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgtzdbafz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gtutdgktou.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtetarezwk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gttorvcarh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtihbvdjje.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtehuusuie.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtucqnuioh.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gttxxffxdc.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtfvcbooiq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gttvotbtww.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbywuhht.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtmaygfclt.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtmvwvcwwo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtdgbmuque.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtgdmfwgin.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtzhcuflpm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gttvetopah.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtigguafbl.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtbpxokldo.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gttsbtecjl.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtzjvaezuc.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gthmsagflz.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtibpxoysm.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtsxchwhei.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtjcmkjbfq.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxawpztf.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtpammjmxx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqfvbay.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtekyypcrc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtrtdbxskw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtkncoubac.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtiknwwred.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtoflmisoz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gttagkyamt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtcrifcbjy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtcsjsamkg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtaovincqt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gtrxjmnfza.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtcfyxbkmt.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtifkoerwa.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtvzzhamdt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtnkkfzsyt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtcmifinkj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gtnaepwhhf.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtzzgirfym.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtdrkpvnsb.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtlgkewzyl.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkzvzuuv.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtoaxyfquq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtzgbmgooe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtlrrzlvgg.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtmuuoifeh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtfgyqthsa.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtvbxnxvnm.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtadnmibfo.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtqjnqcyof.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtgpvvtltv.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtehcmhegp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtrqxlshkk.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtuokzhrop.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtedhokgrq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtydphbfwk.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtpxqgrihx.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtsclditui.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjbebhhah.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtabhypqhh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtwcbbzrqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtjjoboyel.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtnrcfedvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtianxaimc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtjmnxjsaq.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gttryqqupn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtirqgqqby.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtooknefhj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtrbrswsiw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttuqmijug.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtkspoiros.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gtnkglhwuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtqphoresj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gthiekuiyf.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtpwmytugi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtlaktkhht.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtlnixyqjk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtdxqfdglu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtwitsipah.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdlscmfh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtbbilgtes.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtzyqtizzf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gtwqdwffnz.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gternppgfq.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkllhxny.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtbcponhwu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtgqxardbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gthfykaelt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtjrhpgtgg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtpgyjkmgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtpdgajxoj.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtrqrhqlur.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtjfxycpdc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtkrqbzwph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtdgigxkfu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtimcslwau.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtdbzeynwf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtazlohiuq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gthlighdsu.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtmibmrigj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtjqhgkrbf.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtjnpqunlh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtpyhqzlad.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtlyyculpu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtsflysdmd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gthyfcainw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtlxpooqnj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtjiuhfnvb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtungugdsl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gteagfuhuu.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtjyfnqcaf.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtzquuhpwp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtlfgpcsgf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtqrfwspip.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtvgtplffw.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtupymofxq.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gttxnqypgx.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtuopbxtqe.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtnsrycddp.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtavyiiwtw.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtcehztfuz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtutruckci.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtvvnszbip.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtwxpchlyj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvopwmvbi.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmgocxao.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtdddqbacz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtirdkvfib.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtqzzejouc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtsdbnfnwr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtfznvuypp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtqfrxkwya.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtrownwsuk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtxjcrssva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtwokvcmsp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtpwbppqul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gthqvkwzec.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gttxqmacxz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtrgrgatkj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gteaqeucyk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtongyuzqp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtfyxvgzex.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtfvrfvpjs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtyeclgidy.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtrktnzeji.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtuyapzhdg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjpkqstda.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtsyvgafsu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxcpiqoek.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtphylidsu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtgovgcsze.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtcvsiisgt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtaegkygap.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtevxymoer.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtqbudsdhc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gthibdhwiz.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtirngshdf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtsdxyljpc.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gthdizwhnh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtkejydxvo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtmmiczpxy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfoygqyw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtrniamasw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtowfickhj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtvlteqkps.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtoaakwzqv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtaciazxso.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtauxoqgfi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtetffiumv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtmrxgpsxf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtnsecbgfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtidtmghcb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtdkbdlvdz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtelhbtsdb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtrvybxjbh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtigwiazwm.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpvenqxoj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtaudqrtdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtcejivqld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtimszgdji.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtmzatiltm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtxnemiqfb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtjowmnpka.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtgxvwxiqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtcmsaiecb.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtrxatrily.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtdrzojneb.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbgbiulvv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwjzcwzbw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtbpkimg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtazqitfag.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxgwbdah.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkniijpzw.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqmzjmybj.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtashvshxc.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlrpglrgg.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtetunohpe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtinvwezqp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttmzbjjhn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtgjyoloff.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbvyrxijj.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlstgipyq.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtucobywjp.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtlrnaaifr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtcwcibskw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtqemljvhb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtuompqplm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtfadpssch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtoleshria.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtgnclqyen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtqqqhqhpq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtknbgnloz.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtzthvxnna.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtmxszgasd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtdpysdgxw.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtusdmajtm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtqdoeozgo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtkanmsgan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtlolvfcxv.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtvcxtokcc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtsucfoqfu.html


<!-- 参考信息 -->