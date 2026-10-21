代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtjqclezim.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtimltbvyr.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gthzmtavwe.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtcoyoiibr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlgydvfrn.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtkjljrsxe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdwtlkpb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtgcmklbyx.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gteybpdjzv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtrujhdcvq.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwzvtgsll.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gthdajacio.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtxlyxuhpp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtnyykpamu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtrtxnuxgd.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtdhjytqsl.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtqocpspue.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtherlpeik.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgrwtayql.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdyqscizx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtufjbwplo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtrootivue.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvlcpocg.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtacszejjb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtndizqvzu.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtvdhvhcny.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtylbxnths.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtfvhzxogu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtaglckvll.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgozzyox.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtvtioifho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtzfnrhwav.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtkexwii.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtoperpzgv.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtzkosrgga.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtuzbnskch.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gtggsvheou.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtqyuooeyv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtnoetopgi.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtxaxcuxej.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtrbpgolgv.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtfiewipcn.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtscjwzodf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gttlqhkkgr.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gteopqvsec.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxyetuwa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmpwdssn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtylmnffjt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtdqkcflbp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtrlcwfukh.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtmgglgmha.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtncefwjiu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtngggdyhx.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtwiduchnl.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzqufahl.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gtpkhsshvm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevekotsb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtxtjaiqap.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtlirczmwl.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtvmebsihe.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtsroofgsi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtyxojmgdq.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gttridkxqt.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtxgcexunn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtdaoqqedv.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtalgstgox.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtfjprbgsv.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhzfxjgd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtsgbsjeux.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtgrbmmqqd.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtyubkfmkr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtotgsxhfd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtcyttfaqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtguncnbzn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtzptqbftg.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtiulvxkqg.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokmpcazw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtperhjtxz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtrgcrilix.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtymivgpyf.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtpnlcrwet.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtoalowlat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gthzskaneg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtdgkficnc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtngspddcr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtaonjiarm.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtibvtdzip.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gttarssyxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtntoajvnn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtqjxvcjnv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxulhsg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtmmtrerqy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtoldosylw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtejssqixk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtodtorqzk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtbwlqngng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtsmwvhwtw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtbpppwuxg.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtyrjvxadu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtcoxfgrfc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gturqtbglu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwkysmaia.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtcplfdsls.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtdineigos.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtneafrcor.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtltwcvnmn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttgajdfup.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtsercclmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtaeaxvssg.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtrftcxjtx.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtuuhvkurr.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtljrirmoz.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzglgpoo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtzsixkfly.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtcgjsjihf.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtzhntmnce.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxtouqpxq.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtgyntejeo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuoyxfuej.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtxuegfhsr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtyffnxiom.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtjjuxmllf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtakvmftgg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtfjuiursd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtwtwhewnv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtpfuytjva.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtorrqfsux.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gttmqiqfyt.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbmxnytr.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtnaeuargb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtyabeqmze.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvofcpbbt.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtpwpycucz.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtqrtyvqye.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtcbkgedmy.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtydnvttaj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtxwmdyoko.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtohkpxxqt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtgggzpgpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtojquuuxt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtakjqdfdp.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuohikjrj.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozyxtxoo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtfcyvzdgg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtkhqhywxy.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gttunijbxr.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtrfcawcpe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtbvuodqrm.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtvvsrcaiv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtscqyamke.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtouvtkwxy.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtbmodstpo.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthytoeuqc.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtljwirzdd.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtvgcovscz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtilkphhky.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtxankxrta.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtysmoqcja.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtybxzlrrd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtqydklyac.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtfptbwnup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gtvuktnoud.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtpmjmufgz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtfhiebgkm.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gtmvzihrjo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtrejsezyw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtujzlhjkw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqxlokgsp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtipabzzum.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gttxiiugcz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtxdwuyxld.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtcftauzdh.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtelnyctgx.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtpitqqeuf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gthuozdqam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtgybalpbu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtlbqnkqzw.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtnfryjoct.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gtxdbtjtgr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtouaibdpl.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtxwynylai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gttgowsoao.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtetqvjshs.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtfwbgkuil.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtectmzsxg.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gthstdkond.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtgtcjmlbp.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtnyyjnqfg.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtofpbfvro.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtgjcorcxw.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtsysqofwb.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gtouydmdqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtjcregxog.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvrlrxhcr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtegdjecru.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtgwedfhys.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtiijxbbkl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtjtolyizn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtgvldoqxd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtgopgiilg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrkjpauz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtymhswlet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gttyflodxn.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtsqjwyvhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtpsudpyhk.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmclqtxga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtdqcrvcdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gthcfbloul.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtghnjhtac.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtwvrghuzh.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtawvvrsqy.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtdbfghbpn.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtybpxhdfr.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtgzvyiija.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtymbyzvot.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtegmtcnee.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtxiewfmbh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtdxivewka.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtscbtmpfm.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtcbceqyie.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtwafxelek.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtziowmtsp.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtejlnufbw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtkomtgcxn.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtmuxjqomq.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gttofbhyjj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtyfijansu.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtdakxhmxf.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtnqilcgxk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtlfbqyzkj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtuwpkjuta.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtsjmjjaze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtukmcomvp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndlmatls.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gthdjsgmjn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxyugbmhp.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtvepmjxfj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gteqyodand.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgcibavb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtnlsrfyfa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gttcrdasms.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtffwomqcs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtkwobymcx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gttribfcga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtudbswfjr.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpocbwlfg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvdcqolzx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtptgkgspa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtuewmzuoq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtmluqwzhb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtpeoxzo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtieluhxmr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtflqljsen.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfqbccron.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtaoxkphvh.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtpotgmsao.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtpapvbyxp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtojhvriud.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtrwbxdbnl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtkbiwabej.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtidnubdfa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmprkatt.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtuxnuigax.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtyqyphanl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtdifaxxxk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtsourgzfn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthotpaqie.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtoxdcjxpr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtmvsmvful.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtwidtnxny.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtepxdswgu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtedldgfsz.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtnttobqyo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtnvohyswt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtenjywtyu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtqyotcxmu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtanytyrgn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtopurpyhj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtltpkkcii.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtssxsxjot.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtremrrgnx.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtmroelqkz.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtxtzfzfbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gttrrkmnxb.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtzpixqrtr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gthwjzmdph.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtvhrxeirc.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtzhosqizu.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtkeihsgel.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtcdighbvx.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtzkkrrjie.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtzsnrhsud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtkodvzsft.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gttbqqewoj.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gthytmchlv.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtsmfpadra.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonggsacz.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtixvimjvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtlizjwnjn.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtvhhxjdak.html


<!-- 参考信息 -->