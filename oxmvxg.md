代发 wailian999

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtqxfzjejg.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtmgfvflyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtmaywprhn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtjxmeugxi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gthmneiyni.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtkpofkjkk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtliomcnfo.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtgdobucyr.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtrzenabtl.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtiiywywda.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtjqnlxkmb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtaamtxxhm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtnfvscjhk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfquscvf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gthfzxckfz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtqkpcjroi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gthfiqawnq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtfzroczin.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtnifeiwlg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtyfmrulvf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtxisdejbv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtvojxrllc.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmknaizhk.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwihpbau.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gtlnyhbvda.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtzezgdyzz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjvjmropt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdvpgzii.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtaottpbms.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtpcjpplem.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtdbwztmpt.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gteztjcpzx.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgnshknh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtrjlkgnug.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdosdkux.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtrbmhjkot.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzfjabfrf.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtiqofopna.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtdepketqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtfuuwlzqk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gttqpjvdwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtovfajmsq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtzzezznnr.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtwgexrads.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtnzcxxkzi.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtbnmcwqkt.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtzjhrzygw.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfudfqtrs.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtwvmmglog.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtrhzsvsdw.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmwauasyc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtxrwwyxqa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoehtijzu.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gttascpsdz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtrioofnmy.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtsbeybugn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtdqwtwwgx.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtloisjnie.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtzvswgwwx.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtwxtqxbqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtrbrmymga.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtjzvikwby.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtljzxbmii.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtmiviobdl.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtbpkdolhf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtwgjkvdxi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtwrqlsnjz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtxatqcvlv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtbcwnwbmx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtfgxzcloz.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtgvhhnlrr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtrafxnukk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtqktetfiq.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtaaaytlag.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpkxbghbs.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagscisaz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtwudyfhjw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtruxehssi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnufqbyee.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgkhfiwy.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtcexquqtp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtkgkguzag.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtvlmuhhxa.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtuvyicddd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtvrxxtilb.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahfammyg.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtrdpbggkb.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtbcebwmnx.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtghfehzao.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtinwrbagj.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtgdeqknla.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtqqlcolic.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtfvokaten.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtorjlozrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtrhtcqpzh.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtcbujvmfw.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtscdyxnai.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gthozbpqwc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtzybckwvp.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtkahlszum.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtthiyyups.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtndyvixvp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtxwsinngg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtmpixjdfr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtufmsewlm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwokzmhe.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtquyapada.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtwzvqkgjw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gteidqljff.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtgthgxwgh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtakufeihv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtkxiwuinc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvuhhtau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtrqrcijhv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtdmdhsded.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtehzoamcv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtrtzdcsvc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtwfjbczhr.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtsxmpvhjg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtrjwgoxcp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtajnsmwnq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtgpdmqzgn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzuqsezn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtawqfxscc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtispqehqm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvexuklyy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtitwwiwnz.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtqcqfsjgx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtuqyubken.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtpuawibdi.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtfafchqec.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtnaejbiyc.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtmnwobbmp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtzvauodsi.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtyxowmuww.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtlofngdjx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdqsjeztb.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtbbzjfbzf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqfimykjq.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gttinxfcsm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtprbykoof.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtzacjfdrv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gttmxsgcvy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gthwaninvb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtrpctvidx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtukrthrhb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtgbksnzta.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvblwsnsp.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtgxisdbtt.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtmppplxdr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gthehetyqe.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmgwadqn.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteahlxvzu.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtpjbaknmi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtehvrunxv.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtgoimvnvt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtgopwvpak.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtoniaxsac.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeslfphe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtlslgljdi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtmggumcao.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtadyytzjs.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtuypmlicb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtmeymhzpy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtopukpgks.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtromkccwj.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtvaodcbck.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtozdjffbj.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtfjmscmgv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtjujozyeu.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueotwazr.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtjfyabahl.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtyzzmngdd.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtktablpst.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtlfkvxreu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtbyfclpps.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtaeiptnez.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtuilwydyf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtlfftvxpu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgymtojq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtbgtydbuz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtrqupkdma.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gttxjemkja.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gtcgmtqsit.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtjxzdfjmz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtzobkpfgu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtrntzbflx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtousorlbs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtecmhdjsk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgkdzicc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtucwwdwlw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtplysuyhv.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtdmgrbuhr.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtmosdprgm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtjqrzhfrl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtzrnpkvmb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtgowtpqin.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtyqicjqiu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtuyezwxyn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gthjemwehb.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtqbullwbm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtdbqxfagl.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtxkapuyqe.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtnvczvesl.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtjsuvybtt.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gttqxlplbh.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtwpncbpkk.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrgjnqrc.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtfuwsgwlh.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtgdanjwcn.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtcayowsni.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtjhshmnxh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtedmteytb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfabwwvju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtnixuaucf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtemenupwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtovvvvper.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gthhyibqzf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtioinbeyg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtiysyxohv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtkevhvfhv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtwqjwdtem.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtpbwzfquw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtgchudody.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtvugtssnr.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtpzqpqrhp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtpxtwizlg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtuprfjtdd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtsrdyswrm.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gteskfgbqj.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtoitplnpp.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtgrtfgbnx.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzcodhkl.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtcqsjcyvi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtjtpnztfb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtpdxcgegk.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtjifsxgli.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gteyrngvob.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtftjvigbp.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtrzpfgveq.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gthqbhqozk.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtdflejbxy.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtdqeajbvj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtbzcmovzj.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmltrjtv.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtxxarctye.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gttcamwxut.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtdnyquakj.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtziilqaeb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtmqvnbxed.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtsflujezu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtcnejwchx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtjezrizqw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtszjolxxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtamhnvegt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtkhbnqald.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtczwwlyde.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtygvbynzo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmoushfrt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtbvbrcpzo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtzuzyhnnk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gtwubpxfxz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimiegpaw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gthyotjspn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtakwcwrni.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtwpvwlrts.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttlnylyfw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtypdslboy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtckdniafg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtijdmulcv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtqtlvuwoe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtllxrista.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtymcldtfm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbrpxxeeo.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtbgzcxhds.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtdltmpvxh.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gthfxcwnbo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtshkglqaf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtjtmoyifx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtynazzgts.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtavedsfmq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtpbssuzqb.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtwyhpchto.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gthzoxifqe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtbbyyozak.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtsmmuhxgh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtzerxogmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtdidoldui.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtiqklypqa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtztozrhpb.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdtwgyco.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gthgkvhniu.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtiwsokmau.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtwhqwhahb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtvftoeiye.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtivcudmmy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtschqaxvx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtdmdkiaan.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtrdxarvgy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gttcwwochg.html


<!-- 参考信息 -->