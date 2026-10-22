代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2dmagbmic.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2xzcntkmr.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcgbrgzg.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2cqzdbikf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkaywaob.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2uzqtnuvd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2qomahrgb.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gt2qosbxyan.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2weouyzwv.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2zyfhsvux.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2rzfunqjv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2dqrpsmkn.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gt2mtlfpdgo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2nvuebmuu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gt2basotfbv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqofavkw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2ebmairas.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gt2nffwmjyg.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gt2swpztdcf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2nmqgbctp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2fmwzdddy.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2vjtrjwqg.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2wmxhupka.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gt2xzmwskwv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2oxabpnbf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqamoep.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gt2cwhbcsql.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2mgxepzru.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gt2qqclwggc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2mzkmavas.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gt2qsbqziqg.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2smemzjmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gt2gruyyznv.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2bafyzrhx.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2sacbxcfk.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ivucaevh.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2qzrmcdms.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2kounmrqt.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2rjppljsw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2wxzifooj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2hpjqpmze.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2zaizorjo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2xbfpnddg.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2hoghvgvg.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uohahqwz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gt2cxkwwdom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2eefxjoek.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2xedzjqsh.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gt2rqxdmbpz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2pgpzruaz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2dokgqcki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2wwitlqjc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2niutbgqj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2qaapyvgf.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gt2reskvvha.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gt2epscdwbi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2dainuumy.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpesgkzg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2hlybhnym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2xassoizc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2zxgbvvod.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2novxhjma.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2fvsxwduh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2gfhldyie.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gt2lkftzyno.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gt2wsrvosli.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgujcugu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyzkomea.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2dwpujcvf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2swrlwqyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gt2frbuwamg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gt2qxarozre.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2znelgodr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hxairxnv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2pzclxrud.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2ckqxjvwo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2kbeggxij.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2urhnjjcr.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2lcfarnrg.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2jgsmwgko.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2vfkpeuah.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gt2oefmnjew.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywrggyhy.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2pouduyvi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kytlfohu.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gt2imcsbppn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2iclyteqc.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2gtvaxudd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gt2sueugwgh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gt2rzhcgudo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2usaxevgn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2xiuwarqk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2xviooyhl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gt2rsaizysc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gt2ysyblebk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ysxjipyb.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2glzunolu.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2upmwdset.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2kpwdmvni.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2hssrxsqe.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vfashilq.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2nyunglsv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gt2ysgzftcv.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktiquypd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrolejl.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2zaswyumx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2ustrkxsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2tdseppxh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2chkuedxl.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2rnryrvzv.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2gvbtadmd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gt2waoivpvr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uawkrlby.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2rxwxbqwr.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gt2gfkqnvyp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2huoeprmy.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2sdnevpdh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gt2rnrzlpmu.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2xzigrruy.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2bdxkzhfw.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2yhaydpms.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2mxfsnfjk.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2qfnqlduz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvcpaqui.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gt2furzgykt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gt2hluhulnn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2xplxhktd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gt2awmbfalk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymfpjfcz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gt2oxmhcjsa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gt2pdhwepqc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2nwyyzlvv.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2rjbawjpf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mohxrumo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gt2warabnjb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2dxvclgxf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2mrvioozp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2prrppmtd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2dppriyrb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2atvgyxgs.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2trsilhdy.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2tgljwite.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2srokmvhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqffxcot.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gt2vjprvjec.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2kevldvpp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gt2fgucshsz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gt2lmxrwuxt.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2vlaqqaft.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2hpynaqji.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zovgpirk.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gt2fnfhsppf.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rastcuyn.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2yujeydme.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2dkbpkrvj.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2hdenwggd.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2khxsspvk.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2sjrsgscy.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2xuhbfgsc.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylmrwqoj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2mgwzbdug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2hgkuafor.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2rymnzbrk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2iyrscrrk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfubxtfx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2tnhgfdjy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2nrqnqmnx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2sfupqylz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gt2kzbvhzof.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2cpdmccid.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gt2yvadvtfk.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2twiddcrd.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2scroioih.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2nketdene.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2jiicgvzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqqzjdvp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsqzgprm.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2clibvrvt.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukkgnjqb.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2onatxeds.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2avtrvnxg.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2gbwomyra.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2egswtbbx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpdsqpvu.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2uiljpetw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2kokaspmc.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2iaehruou.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2nbdifaco.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gt2ozcowtzt.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwcvlvll.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2mceqyngq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2zsibsmvw.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2pfczaqme.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2nadwmfku.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gt2zdvogqde.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2trlxzmnk.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2odnnuzbd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wklomagb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2jyiggyzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2magyfjsi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2qtcvqpqn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gt2ifhbllxu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gt2pqppuhcv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2acvdnddi.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2rnlbnqwc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyyivwvg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gt2bdnmghyh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2qlynbkzy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gt2lxnckbir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjnprkmu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2jhhbwtji.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsjxnjuh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2wdragifk.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gt2spzxvyas.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pcdzrggs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2nqqzgzft.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tbbwvmeh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2uwqxxuxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gt2xvoryswb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2dyebpvey.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwivxkp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2glhbaswl.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2hyuiqjxx.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2wmxyxnex.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2vzwykfoa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2jiibfftb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2mxmsybak.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2ggpszfrr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gt2vmlhbuzh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2fpzyeslc.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2ezwysnwm.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2ufempxfu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2pvhkjjrr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsjjcwpq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ihrmgctm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2amxyjnic.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gt2enrfluhp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2uvtjwdrx.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gt2kzznacjl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2lioewikj.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gt2zdjzkqmy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2rvdxvqtc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2oizxrikh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2osjenezl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2bkqspsor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2omyyttaw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2loadjntx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2ewluaetx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2mfaifwnc.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2jtrvjjdv.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zysjwslv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2grahfixk.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2yxhzxuaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghxxtbbk.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2tawddxdb.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gt2rkowhwnk.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsfvmuma.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2ttpstjza.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2okvhtzhq.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rilpcatw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2dswjtwsh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fzdyizti.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gt2hhdszurj.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2hqlazfbg.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2udivhcou.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2gdvjmjqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyzjfnoy.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2sxtdfixg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2frwmbqmr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2bdixmkri.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2niopansj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mliioeka.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2ktzzogma.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2onvbzppg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2gmqlwwhb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2vxxqalue.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2zwyjdnft.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jgknulwn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkbgvtfg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2hyudasos.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2wzivngrb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2dpcwltms.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2zjejpcue.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2psknxulu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdfybipe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2acdkuodt.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2qfmrhrbg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wcxjzfxb.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gt2jlxfokor.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2itgybdoi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2xaowgkny.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwghqyjv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2cqhttoay.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ctzsetzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gt2cpythhfq.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2unnoaqev.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2eclbykrv.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ksqobqez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2tattphak.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zquduozj.html


<!-- 参考信息 -->