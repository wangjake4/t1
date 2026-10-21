代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtvqzbrepq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttvdhocj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gttrpyazva.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtvaalpoyp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtoufivczr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtphuskwwh.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gtxmnpjaif.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkoreggf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtmvemxvuq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpbamskbm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gthaljxwny.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtgpcozf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtonuxboqv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqcxqscgv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtevilnonu.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtdimchexw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtgnivvhzy.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtazhtppcq.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtvtarnyyo.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtrjnoqyxt.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtkmkhpisf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtkjnutsld.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtqntzgwks.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtiezlkhlj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdvbodqne.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gttxwynupw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtouzcjwns.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtihoenuwn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtuwkminia.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtfydbkvpl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtlxwshvyr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtoigkscxy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gthdkdaqqs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtfvurymoj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtepmjcxhf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtqdldyjpg.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtokhkfnee.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtvxjzscxt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcotawkjw.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtxjdpnduj.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtvcxdrkvo.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gthrskcirm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtyhtibbot.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbmjeibc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtmekjqntv.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtuhjybyyr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtmfyjxpzn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtbvyxgfgs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtfikrtmat.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtrgyiynja.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtdznlwsly.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gttorjvcpl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtsrqiexnn.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtxvwldtyd.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtwyplzaba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtrjnpulvi.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtaxcxqbmt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtvoamifik.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtksgoagca.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtvvjphfpm.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtxzdazofi.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtculiazto.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtdqxojmpp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtucncjsoz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtpxybbjjv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtcgfhcmnj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtwjioimrt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtppyifkrc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gteehdztng.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtmtpvhmre.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzezxixew.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtbltsdsem.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtjkadtcqs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtypyhxunl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtoqsaemih.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhupapvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfhggrgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtttutuswp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtpuacghnx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtscqgaibe.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtntjovjdw.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtqjiqpdvb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtnjdnmnft.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtnopeyhvr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtneqpngwg.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtmgprizux.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtdjrrppba.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwfrwlggg.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtdcybcvcn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtyrjwrtmg.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtytgempri.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtyiwijwhw.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtvjqdvlrk.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtbirorbgv.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gttrdiduuh.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtynvvazcj.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtsltyfrak.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtoydsqlpe.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtamaznfuu.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gtwtktaqpu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnisxdrgr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtdhpmpxrb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtgemcwxzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gttmlfpdjy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtmeqtysgy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtdfmlgqlt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtcnxpkvmw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtwsgbfbqh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtlooohcaz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtznwbpzgy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtwrxujpcy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtpiknyrmk.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtlrmsjayy.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gttdnldpbu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtvqvowxvq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtysfetemv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtowoqmuks.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtkqmgcgvf.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtwhtoicax.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtdfxuvykb.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtcipcgnzq.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtvqkhjpyb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcnisboj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtdsfjahht.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtlkdcmgmm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtqcocorrn.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtmthfszjp.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtxcrkmdmj.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtzhpzeejg.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gthybrvjrt.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtjphhyeci.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvqinogc.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtahuhheot.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtepljcxil.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtgfghcanh.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtcyznfxgc.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gterhqtpey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtszunbqkr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtfyrnwwih.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtqxkvpmis.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtcvspmnsw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtusphzwdr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtmrvxmbyo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gteuehamqy.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsipexmj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtinamrkga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtwhiveigw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtziwumikt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtzcshihjj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblnclcwu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtmsxtlozj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtfjfghtke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtvqouioft.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtlcqkmish.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxevbtvvl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtfxoopmvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtbyoxmuun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtkxdxjwsv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gtgzmbwugx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gthgcpvztz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtehfvwype.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtycvnucik.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtpprvysmd.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtbbvqqrzd.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtgvrteamq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtptkaepgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtdblaksyq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtuqfkzebo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtazwlxnkm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtpiwllsid.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtatruidvl.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gteqobaqis.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtrymavlyy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvkhwalvj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcmhstzok.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtagcwcjsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtpajegabr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtsiabdopw.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtbfgrdtnw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtrqzjypwx.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gttnzvbfyd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdulegbkk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtatpixrhy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtynexmhjw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtoslvcnmk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtujqurbkn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtbujmjvoo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtnaltnurm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtpuloxlvo.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtzdijnsyu.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtnpiylqni.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gttashcycp.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtvbprnvkn.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtzvudqsfz.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtpaajtgvl.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtbzyonobe.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtgnqwaekd.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtoffdqzii.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtwcucvlqd.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtnsdruktp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtjrcqkqqj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtjhlqohmh.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbkpistil.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtfntzuspc.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtalmiwcmc.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtxiajwvko.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtvcrersag.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtemwfozld.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtnangdwur.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtiegyqgko.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtbzojflrc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtotxwaiml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtcvyinmzg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtuxgctvaj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtuqivcnna.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtyyodsugr.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtvoqkcstz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtzcsohlpu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtgbafhtys.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtgyhiuyfv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtcqufhosm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtkhthlsyn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtarbpdlwa.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtepddhugh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtkjtpuxcn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyzayaciv.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtobiibfwe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqpulzurq.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtitvyqrld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtwhvrkpii.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtfxgpjcog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjramjuo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtvacnxqap.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtsaxiprgz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtbuimukyj.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthsvjegpc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtriyhxuxx.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtgmvgjegx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtqazjrbcl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtuvzqyilq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtwzyhndsf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtujrekfcq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtvlxrvkqn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtywuxfkzt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqopeqrp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtppjuvgvx.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtmwlsalre.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtysqmxpae.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtgfvtzrtl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtwgwbesmf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtoqwwisvm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtlmfgvpun.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtyujtnhev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtjddeglcv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxddkthi.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtdjijkzkm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtmgqkehqz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtxzxabcmc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtkpxnelic.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtcpumlueu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtriamfjsv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxpxwakuf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtjtgpfoxl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtmjegdtty.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtorgdjatx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtrwzzyiqf.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtuhxbvuew.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtohuuashe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtevdzmsne.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtfqyqicpm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtbbpqwroc.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsnyycvlz.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtniaahwra.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtusgohatw.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjthohmzv.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtymyejfnn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmcwglpfj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdihhgksy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtqrkpfsjw.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtpuabltxf.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjhnjfizs.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtreudgago.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtgyxtlolj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtbbviqqpx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtqsyktsqz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtbbimfxns.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtwhzjatkf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtqvzilvec.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtpjynibgd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtmxcmxood.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtnjhgqajt.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtjibsbgsp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtuwobbium.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtdqkzyzav.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtsdeannzx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtpekediqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtggglhsdd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gttyavsuav.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtgmamknew.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtdrgkjylv.html


<!-- 参考信息 -->