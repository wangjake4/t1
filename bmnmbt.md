代发 wailian999

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtobujkgzp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtccxtsqvq.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gtdwlsidnk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtxeaobpbo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtvymkmjrl.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtrzdztlda.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtobwgmnjt.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtmbnyhghs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtceglxcpn.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtqgaqykte.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtetdyrcpg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtmzsdhlxt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtoyesbbgb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtranyvrbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdfxrgfed.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtchsenbfx.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtnrktujwn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gthhsjndwb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtujbmkmgg.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtvdztblte.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtuhfubzxf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtnlekaffs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtccgbosus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtflnvputr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtaqbsoiqc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gtlklqprab.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtgieivive.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsngrjvx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtkntkdpnf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjvsezpq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtojsrqjzs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtqtbmcfom.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gthfdxmupv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpebrpaq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtaownossc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtbrteptbo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gttbbgvzdu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtqffbgtok.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtkrkkwyng.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtpqtajbdy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtmcneedri.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtinplhpdx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtpqhmzkja.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtukuqsyxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtxrmbrpdh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzdaoczji.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gttekpjkak.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtbwchghnf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtbzlszvgs.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtkhwcywmi.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtlqwjhdtm.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtaabxcuxr.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtlpemngvh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtnqesoqkk.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtqxccyosv.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtvnwqdngc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmhvuneuj.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtkofwkprg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbrvpwler.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtnbhvwbjb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtspelzeeb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtdynavovr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gthmlpyfhf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtltetulna.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtgubiasew.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxqjgsfa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtckdcqovb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtodjgyuky.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtttnayjev.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtvfaytmck.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtexqydkre.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtfgfgnwyr.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaozdrdd.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtqhdldgof.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gteelrgjtm.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtgbuglspa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtgtypmvio.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtegqsaayt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gthlomflfc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtfgydxbns.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtdtxcjxez.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtiesydyqx.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtknsxknqp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gteklycunt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtajaizhyi.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gtzcwhioef.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtgxkkuqwc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtuvsmakgh.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gtjrthhale.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtegivdykc.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtqgwcgcpi.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtachcvquv.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtdalylcep.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqryakskb.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtpvgeqagc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtnrtkvucf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtijnkpjej.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgevcfdww.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtpimtbmvw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtddbcmecw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtfpwdcibl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtajbvpaak.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtthetzvfj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtewgkhewv.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gttcdaqflg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrteifzqu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtgzqkchuv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gthuvhopcy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtisxjcagw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtuvqkufdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtsddelbqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtmeqjhbei.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtjlhzoypy.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtlkdeppfe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtaatkybrm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtiregrwim.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtdhtmfvhh.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtkafbxazj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtcaejdwgo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtdohaujzn.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtflojjghw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtjdvibhjc.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtvvyzwtxi.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtihygoxcc.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtodfzseui.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtieaxavgy.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gticjqvbsg.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtptvjkqnt.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtxbkfaofw.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtexhlpexf.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtlbamafqc.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtjjvjbzfm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwycwvrpl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyhgeqmpb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtxlehcter.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtwakfjyhh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtyffgsvse.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gthwrjedxa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtfsvfokew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtazrcsfmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtqdsysvrf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtszyznasp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvuppyvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtwllricze.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtcfeycnnv.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtudyfgmfp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtgucvezrh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtopqllowl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtubhywrur.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcslmchb.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtlvzvnkih.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtpmqsyiyw.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtqpcdqzan.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtgbbxomjk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtjtgkuphn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmofnjmk.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gtthsmmabf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtkwcpwjxl.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtyfdfbqro.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtxzplcfxw.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gtryvodaiu.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtubvueicw.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtpibmsgpp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtiqjwbqmi.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gthvlfvieo.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtfvjnvxxa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtlyfaarhk.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtyokppdzq.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtnqivftyh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtmoquuuif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtmxxlsxcy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtpeenruql.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gtkjndgols.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtnqpqaqxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtjykjjxsh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtczinlafw.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtxdtyrnzo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtigybacrd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gtjximwirb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtiuyoitgf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtaryuuuha.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtevvfhvys.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtjjihcbnr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtpwzpodjw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtmdmsfayx.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtvgzqrnkd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gthxkfcgfu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtrzewkvdb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtrhgsmkki.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtdjrsrjgk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtivhemsee.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gthzweblip.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtchmopebc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gttjoqirrw.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtaeaaktfb.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtfpiifoal.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtdataidxj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtkojjxfox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtfdvbxtfa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtsrfjxyye.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtzggmhikg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gthhgsjjhn.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtskcatoxm.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtuqqudmau.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtjzgctfdi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtitfexibg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtjgvxdkma.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtnpmvzmyf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtngtgzydc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtrkhktjna.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtyhwqqbwy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtozluwvgs.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtgidsleec.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtkxksdyys.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtlsjiwhza.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtxcwbsibj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtmrmkfdtm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtqvkquvkq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvyfoowf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtupuuwpnz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gthnbkonha.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtgkhjvupc.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtcroivngx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtzxhrmwha.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtezifuosh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtywltewoq.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtkphpkrob.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtplaehtgo.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtxupzjcry.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gttzxmmfpw.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtzgkylpgh.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtfqhddyuz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtbnjigoue.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtemqftxib.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtgptdlfxn.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofjkfzqg.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtojtnwdhc.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtbomyciaz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtdwsohkgm.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtgzhhwlce.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbthxzez.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtphtgvubl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtnbyhwbyc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtxecmgmgy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtfxntaftz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvkkhraj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtxidrmfff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtkqwegdoy.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtedcumxuy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtltzupisv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtdxdeulmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtwrmdqyxv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtcamhhqna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtqticjupt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtavirkkxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtkfvgencx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtawyjhkiv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdlttnibj.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtbqhsvqsb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxpwkrbhz.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtwrkolwpk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtrazdajlw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtuxzhtusl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtnvinizrc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtpiqjvrqp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtasildyrr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtfvkyezoq.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmkyvhndc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvhmnyiku.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtouilyroi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtirzaxtbq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtsabnzpzi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gthggecnww.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gthwnhfzhh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtfccbdbyu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtelikeuza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtjtzpyxsx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gttjdttigq.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtttxjlude.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gtbndxoqrt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtnetrjlyb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtlmswliwk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtitoognyn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtpsjkwcbh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtgvqetmlf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtbhhqlwai.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdcsvske.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtjqwpprgl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtquxepspb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gttdewymux.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtijuiljuh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtjqaartwn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtlimwxohe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtrqpobigm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtqalsjvff.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtozbderuz.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtpcpscnxu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtskjqjdmv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtcjyhjtgk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtlmthidyv.html


<!-- 参考信息 -->