代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtrbkjierg.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtipeodqyd.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtabzpewpe.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtaapakbri.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtpvaipvte.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtyxnkdict.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtnseyxqxe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrcybpckc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtovrorvbd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtxtqkbqwa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrlmwyqj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnwhgtfx.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtfwpdubix.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtxmhbwzwn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gthtprazqh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtrtwvmiiy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtddzcamvb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtvcwycmtz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtkrdghvsh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtkoghpwiq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtzkdafyjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtzdwgzmop.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtrgpcsjhr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gtxtnomsrs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtggnamunc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtfbsqnniv.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtkvjovwer.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtksmaflpv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtxdvzbqej.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtrndjwvxg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtishoykyk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndmbihxg.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtisarpdkt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtbqytsycj.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gthpnwzdrv.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtbbkhgxqy.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtzigjydcf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtofqkcico.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtelkmmrrw.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtrgpnexqw.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxpvvzxzi.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtjytfjdqf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtwzcdiccb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlifvzaxz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtmjqshpje.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gticdrpeex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtmkqlnltj.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirylxnkh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtxnmzwtsa.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtptthgcsa.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtnobjhhnd.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtyqvxukks.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtqsapwrvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtumyyjhzp.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtcljbsaaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtjgyzmzdi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtjpqlmxyp.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtdiuliitr.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtmqlqvpqn.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtdoidjdtl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtzblqiiqe.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtrgtkqizb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtsxhdsvxr.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtijmlfyjg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtyzugviwt.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtarcsxhaa.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtoebhmdmd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtkxhxzirk.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtzgnvpyca.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtwjcdfddp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtvllyyuvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gthqjnvmpx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtljsdjlvq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtcyfnylnn.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gtzrcygart.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtjrzlwyzz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtgwjpuvbn.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtzyvqqlyk.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzaclvnbh.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrxabwmkw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtwttcjnir.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtobjrjkow.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtkoodqiww.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtgivegnyj.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gttmkrqckh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtagvjgqbl.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtqxfhdhil.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtnhzllnam.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtyzgrpwcg.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtjdsycdzf.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtrfdfmjdy.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrtplcahq.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtyulktxrj.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gtunhxcbna.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gttpcnefid.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtenbnmpyj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gthqmklqeu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtkpernhst.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtyuqcndpf.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtkflaanvu.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtoggenjim.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtnkcbgbzi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gttrlhqqwr.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtjqvmznrm.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtvbyxdyhs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtmzoswczl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gthremvczm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtnxgxhebj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjicyzzfb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtmxoekcdx.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtluqzcuxt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtdfkonoue.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtfzerzlvp.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtppbuyjxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtmuijbgdm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gtqlvaiqyl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtoqrmkzvq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtexhgesdv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gteeotzgji.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtkmaawhiv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtfpowykcf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gtuxmnlyvu.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtrybdmdqw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtlgizggbm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtwwecwdst.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrqeioza.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtoxhegtgg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtivhdsunk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gttbfbbdtw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtmjxeukvg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtyqssrywa.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtjwihikhb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gthdeadtoq.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtmzokrojv.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtcnvmujgy.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtsuoizpky.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtcutaursu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtcliwfshc.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtyyjcnjoi.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtarjiekyu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtljadgcoc.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtvcasacgw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttzzgouti.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gticsozuys.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyvjxvek.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmbojlsi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtozosbxfo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtazkucjqn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtynkgokve.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtnlrorugn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtrwafwjnl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtiqdwzjfn.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtmvilnzdf.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gteztxtnmq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtobrtycfe.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtpumcjood.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtoeddcvdy.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtwyxwxmvc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtfzcvmsuw.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtkjcvkelv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtnbnwmtdu.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtrosaqlxf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtmrimvjug.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gttqwbdqva.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtufsibmcm.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtizbcvloq.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtkxuapmmf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtjzxsuvku.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtgvxandic.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtaduzgnhu.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtjnwqkulq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gteidgnnoa.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtfsqqclge.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtzjyuigkn.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtsodjkway.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtkqjajgzk.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtjbchqfrs.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtfaancxmj.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtlemerozj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtptbykadq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtcuznvoym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtahgjoxin.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtwbnhyprd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtzgentgso.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtqgcorufp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtedjrbqwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuavoxoy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtwidlchat.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtfiipvnxw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtnbpfmwxt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtjsmojeiy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtfncqxopa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtukladhgi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtdzmqxdxe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtymagyjiv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtnbmoewmq.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtjvqjiwzj.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtrmgioazx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtgjhgjbxj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtdlveasis.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtfkiqxokf.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtktmxtwbw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtpfsxxvkw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjfwtwlff.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtevvocgsf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtpbnymutx.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtjprpkpce.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtajjnuplf.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtwiglhnvy.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtptmfzvti.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtskzaolec.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtjzsvefqb.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtoqbxcaxe.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteleonayq.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsywgywe.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtdwrhbmrf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtbvkwbpkj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtzhvijftw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtscxpovxd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtgtmatgiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtbzevuaxp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtycoreojx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtxdsrpmhy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtdezolfnt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrecmnki.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtczkwqnwm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtorrpomkt.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtzqudgpmb.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtazyzrdyn.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gttsxmrfyi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtlacjfllh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtsrmhkmen.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gttosjdmqf.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtxtniqxzg.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtbskxjbod.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtbmmhvsca.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtvaskvwnf.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtaujohjir.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gtinphwprv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtpnpmxmns.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtrwlsmgqp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gttkafkofv.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfqtgbgk.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtjwgnnojo.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtrelpxogi.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfihutew.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtbtloupiq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtemflpumb.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtvinrsnmu.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjofytfbt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuhvjgiz.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gttpkqdqbs.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtkbbnmjcu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtumerekbs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtioeddduk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtkacjmlhe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtysvrmuek.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtnqwnebev.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyamvafc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtikjdiuoa.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtohfpkeyt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtxhpsytjc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqpsxfdn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtnannmhvz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmsyrdnt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtgrlosrir.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtqufcrwja.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtaiyxpcqf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtpfltfzqu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtnfoqwdtr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtxmxjmgps.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtxsebgmqg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtzgzqenpb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtrwqncbyq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gthizlrwea.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtynkikqoh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtihiattqx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtgyzzwwpm.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtbhfwudhb.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtilaaxywv.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtlvewkiao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtzpzdvvjc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtidhwfkha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtfdizpqcn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gttaywxtdh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtfktxfnnt.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtlwriflha.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gttnpweviy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtlecfmeyt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtmohxirjw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtdwczdwim.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcgtiizxx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gtmvbrndau.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtnidftxdb.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtoutaodri.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtpwvugdiq.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjdwhefu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrswruplo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtoztoavtb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtrazsmowu.html


<!-- 参考信息 -->