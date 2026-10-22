代发 wailian999

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtskiwrfbr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmkiuxzi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtdofnmyul.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtjuyffaab.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtoyvatptb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtkzrcfwjc.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtshwlikzd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtlpyqeaes.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtjcpiyugj.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtxjavfcfq.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gttorvatvo.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtermxkmhz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtcqlhiufa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtyvdsimvj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtibbikprr.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gttoajtxir.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtptaqnflh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtbzgfakmj.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtgxmzyyhw.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtjxvmegtx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtycfdorwi.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtrahvherz.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtcfnkgqef.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipmxbegr.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtqxsnxuhv.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwfxletp.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtjtdybijj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gteesttyol.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzycgtkea.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtfksjzkab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrauxfyn.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtzptjwnah.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtuxtpgetv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtdctabhql.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtafxfavfo.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtovkeajgj.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtjlejoyaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtwfapbala.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnrjxjrz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtzoumblru.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtjffofofr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gteevfvpqm.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtqkqdqqpw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtdneuskkd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtlxkzigmr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtdmlfpbqp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtdyfngcml.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtestejewc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwskqrqbw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtwfxmssym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtxlpojzhr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gttyovdlnx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtuaoxther.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gttkiodegk.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtanmyecxp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtpfezgdnx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtckrglpvm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkoxstzt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtuvoywkhe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzimrcjwj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gteesctbpq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtfbblfqnb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtaoqrkdal.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtjpxqklwp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtpguzznfw.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtardcwozr.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtjhlreojd.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtwqxesebk.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnroiovt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtofaoumzg.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtpkrnaecc.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtpvgqjkmt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbhceulex.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtuuwtyghm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdykxduck.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtfgvxatmi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtrkggzvnd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtntpjolot.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxnrsneq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtsudvvjvh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtorzwgktd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtvkmavuxl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtawtpenzs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtvkyqwfcd.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtfoyetvbj.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtnjqmkjle.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtlhcbveaa.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtmlezlfmd.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtvjwxpmzi.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtrnzjvzav.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtuyscjfnn.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtnkvouulh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtvddlhvar.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtmvjqsyhu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtreycuror.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtawmypdxv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtdhgzhbrd.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtyykcifdb.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtmrpnqzbi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtmprfazuy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtrffrczff.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtutmwfwox.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlztxdaee.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtznzvtbku.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtlebkrelu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtnvhqmiwq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtplvxkrmf.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkffqamc.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtitbskywm.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtpdgdbdco.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtaqjzlilq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtkfwykjpl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtdufxbwhe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtxlpgllcd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtfonrvdhg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtxsxvbakh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtaxxftwnr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gteqgzbjon.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtpqutdugh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtmbwazjnt.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtdjwbkcyw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtaxuwxscw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgobkkfy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtihlfocsk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtptemsonc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtjvhxwhpw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtagmyflte.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcssqtyyn.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtswpxtvxu.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gthmjtekdx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtwhxmtwuo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtawgltegs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gthgqbjdpl.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtqjvhvlfu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gttlxwtxhf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtlwlciadq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtsponjyie.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gttjakcbti.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtnvxglreh.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnebccwy.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtykrnovtq.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtahkphvfb.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtfhwubqif.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtxmgjngge.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtfmvgcfat.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotwyvunx.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gthemkmtfk.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtzzxwzhyi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gteczvcbey.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtttiexsnt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtowtioilp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtqrdyxfbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtccebwbyn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtvqapvxxe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtklyqchoi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtpxzrdwps.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtjughqwik.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtrcissijk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtischclvz.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtksuwwskp.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtwfpghaed.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtbcndhtnh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtdozwzlgb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtasvznrle.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtuwbifuuh.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfsfyxzlf.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtkteuxfoe.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtyvenxcdm.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtkhdddzey.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtltvfsvfa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtsqwcalic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbxwoygy.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtqqanijsn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtylvbmnua.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtwhekdepi.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtwhqqzoql.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtqkbgarig.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtapwycnja.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtnqgtsrgd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtthtzulwp.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtillzlgsy.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtvtntctyu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtlliqup.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gttxbbvivn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtwoosxacw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtjjmxvmgo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtpvtewpjs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtqozyccng.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtfylexjvi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtdzznkpty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtcxppsfkn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gttyejagtg.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtrnwhvyyw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtwsivrulm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gteecyswsv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtynuepdfh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlwgttuvd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtbpopemhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gthdbtewzr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gttejthjmj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtvumefqpo.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtjfawpgob.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtpnzwuaev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gthjhucywe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnudyvbdr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtoehedwma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtikhyounj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtktevjhfr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtojbukujg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtqsroklby.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtkzplvylv.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtrxoclsmi.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtxtfcmcpd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gttzzllqbw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtoioebpjv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtwxaeqber.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfcfxblg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtagqknitl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtyaernvix.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtrvezzkmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtuzjexivy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtrzvlaoik.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthortopfe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtbbcslyml.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtazuweftx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtxeqnieow.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtvtxrtzqu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtxzgelpad.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtxwmczlae.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtjdyxjvmf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtrmvwevfu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtszgdgzki.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtxgaqifdb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtgsybxbwd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpdgbnfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gteyccrowz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtyuehgbuy.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtvbjzdhgn.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtdkdspntg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gthvuvkkgt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtcoykdqpg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtdxmirdke.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtqbfpnlul.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtgweacoju.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtzsmzxide.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gthwgksxqm.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtsvmburnd.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtwednxnrp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtxroyndkm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtadybepom.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gthipgpahu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfurmnjq.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtrxyzywaf.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtuzsnogkv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtjlzbyltm.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtikfcrjyh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtvvngrwze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtumymltbo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtftyxceej.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtgwnxnecu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtqgsjlnrk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtsbzgegvz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtneoxzltg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtyclatogz.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtqiyhfguq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtzhuphxxp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtcobdlklz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtgldkgbbf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtadnxofwt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtuezeggqc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtaieuhgew.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkxqflas.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtwoogsvwz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsgzizaxa.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gtudiwkaas.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkckykvog.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gttokldoym.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtzdstgpyx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtiwlomyzb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtqtenxygr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtsehbnoyn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtqqtrpjgt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtcanttamk.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtoifzvehg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpgpnyhov.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtsaqjprxn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtiaygcnyu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtcxhgnacl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtgecpxmmt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtyolstsag.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtjjomppok.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtktxywdsf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtozxpgkhw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtdbiybkjz.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtfskyyvvs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzgkbraf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gttnngwbvw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gthmelpdkh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtbvntknqj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtlhkmgvdt.html


<!-- 参考信息 -->