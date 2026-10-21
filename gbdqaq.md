代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtplzxjfav.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtptqalrrn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtixwqnkja.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gteuisoxrd.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtfwcqpevc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gttkimahao.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtlyeeybvu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtykkpdncd.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtyucvewmr.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtxcwtgcbn.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtepajijcz.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtdthrsnjb.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gtfjjzxczl.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtciyojrbr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtykgmhusm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtqavqkyzd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtbuxswxck.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtulcbzghj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtgcuzghbu.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gterpikdln.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtsclrsaxx.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtfwwfcvdv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gtvnlqgqzj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiojjvct.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtotcagemn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtaabkthdi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtkaixemud.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtrzqkxogb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtvmmqdthy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtpxccbeis.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtdevhwxhv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtdtwxpqeu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtrayxakyu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtwqvnszva.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtkjhtuheg.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqriifmn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtjyadycgf.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtbqbwygxo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtpxrcwnqi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gturwvspid.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmthszvm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtzruexohk.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtzgmmbtjp.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtsqzrxrvd.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtyyprywxv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtsdlyyelh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gttyoujimi.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtulsribhm.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtgfljykqo.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtruuhozkd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnucmxmgv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtpfifmrhc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gttawlspru.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfpgxxbo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtzmstokup.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtdhcjxyel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtivyfrefj.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtkfirrxxo.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtlaikadsb.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtdnzhaeqp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gttixarqsh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gthyvomrfd.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtceidljei.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtlxfonjna.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtccxrloft.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtfurihmro.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtgbthlqmr.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtgyaargqr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghddevoo.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtdwfpjemi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtjwldsjtm.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gttuisgysw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtxxpuupbn.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtycpatxgg.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtyehvptye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtndzckkwf.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gtwyawbxrn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdczfwxo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtetrywfzu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtvwsfvcwj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtuuloyjcb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtqwpupszo.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtwmdqytoy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtdfswimli.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtidqgjyka.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gttnhgcxht.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtqusmnohs.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtdqcwuxlv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtdmsgrxdx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtqhdzbuyd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxniqsoqy.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtmxronbix.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtktoghvzt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtygfyebcu.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gttjasfnlv.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtkklpcpye.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtbvciffat.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtgabvtzws.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtfghaysft.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtthcpcmeh.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtsagonoel.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuhxpgwud.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtvfudefeq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gtzbfnvefm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmmuxnakr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevvyaswg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtcnhzeeog.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gtvzmbqvoe.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtpwfnrtwo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtulknpxfx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gttqpguhgq.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtajvgmido.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtkpqsjpju.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjlpscuy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacqwnqqv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtmxiqqrqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiqyxhzb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gtbdpphmdr.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtlgolfyll.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtbprcefxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtewpjglgf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclhloaac.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gthvvvpilq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtfbppleny.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtestjzxku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtakrexdoi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtyyhztwsg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdchotiny.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtftryepmp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtdzawwmdm.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtumyocqsw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtwrriiolr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpvylmze.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtxadwoxht.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtwubwvtbh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtgzztjiyk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtnkninmkp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtrvduqiwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtckxmflzi.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtehmexrmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtpuvobqvs.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtejagagmo.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtxastdmqb.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtztipcqtv.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtwpgspsxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtmnqkujlw.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtfvhrlcjs.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtgajwvvjv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyljazikq.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtzpwpeqgx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdjolwuws.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtoagsbevs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtfdymdkgf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gthxqkhvao.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtdzjbchix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtrvpwlqfe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtmtjrqyla.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtnzjkozes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtathrlrlf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtcjerugio.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtnamfwavl.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtvcucyhsi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtlfduoktm.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtjtesjpxp.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gttlvqgjea.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gthjgoquwp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtnxeddxee.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtqwzgwzrx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtuvaloxfm.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtydgqmpar.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtzbpbmrlt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtkkwhcntx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtkaxxumgh.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gttkqcmoyh.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtdqyuxlqo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtkwjfrijr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gttqellbul.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtcjanfrwv.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtgihbhnsy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtckwhuhyu.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtvdogtcgh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtwghpfgig.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtyszepnom.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtophcvtzo.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtiybivpcq.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtrkfckwzi.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtjvrmaudw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtkjqpcmnd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtxgxqhixl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtqshdpari.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtuvvzqobp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtangwoyrl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyckdgzki.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtzosxpfts.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtxhinjiat.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtkhmjxpfe.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtsqnukuyl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxvpmbvv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtybiuvhfh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabiccvhg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtegpvipdg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtinoghkss.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbxxitprx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtjgtuhutm.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtotzqaqwn.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtlphbgzez.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtpfybghqf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtgokswgdz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznkqpqut.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtjqgcnwjx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtoolfnvuj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtnhghwtnx.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gthhhtakor.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtaqdkzfba.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtxcqbvnzz.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtupcwhcms.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtjarkedgw.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtdkuyxpmg.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtkwkaepuo.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtcoinygkc.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtwnrlldaj.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtwywaezji.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtchhchyna.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gtuupgkqgg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtvurgtgwc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtnzblmhzg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtpnwhlevf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtbaesumxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtgargioyf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtpktkbfjd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtlpmaubaf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtmexxinih.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtilegiazo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtqhzbqlcw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtjwpkzrkj.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtpbvctokq.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gthnkibaux.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtjduzszim.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtoqnjsxhp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtmwfcxdya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtlhtlqmcd.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtwirazuis.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtpmvgkwip.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtuzwpvfsz.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoecgksq.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtnateyppb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajhfjoxn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtccmhzarc.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gthzevizrw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtwqbhqsnz.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtgsdsefmt.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtmjrzpdrm.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtgakpprgw.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtrhtndowq.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtsrldkjzo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtlwdnipsm.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtuufhkjbl.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtthpchqtl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gtiximlxgw.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtzsxzokcq.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtjcvtnznr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtgpgqxddr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtcgcohhkt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtddiyimbi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtnlvirvnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtdocnilyw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtmrexpfrc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtvwtgyqmm.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtygevnqhn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gteztoiyou.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gthqysovhz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtgeaowono.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxjpzmstj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpqskfwg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtqllorkkc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtfvulevck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtrviviqre.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtgfzfmmtd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnunhsgys.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlrjemsie.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrrhxrep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujajqopd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtiadvqjvo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtflxsrffx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtoomsrpik.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtsllqqedp.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gttsaqtpwf.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtbppdwubc.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtlyehgbkb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtdofsxdrl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtyxfoqgbh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtputnwame.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtfhjihctv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtgnockldu.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtntsaicye.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtvlrwynzb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtqidkngxo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctjbcmao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtlmifkesj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtokkkcogs.html


<!-- 参考信息 -->