代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtxrcwtkxo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtgnkjzbsz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gttriecypn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gticptvpbi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtyplugqzz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtqasdywaa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtsygawnwo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gteniycakm.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtabppejeu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gtwquhzugh.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvtwmavx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtouoebjsc.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtzguudv.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gttewtwwvr.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtwynfkwen.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtwcwfxvkw.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gtwqameeus.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtuxzeqkvw.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtogywgonc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtvxamypcy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtaytdltmk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gthldiiibt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gterflhdwz.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtefjqoxpj.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gteywsgqfd.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtjgiegmkd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gthktnbcac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtxayzveko.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtpkrkpn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtpecyclgi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gthvgcjirn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gthyufbrru.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gthizurkyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gthgryqguu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtedjumpse.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtnnhpjokg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtadqenlca.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtgvolbxmu.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtwhrijjwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtuozkqwfe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtrbkegpqq.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrjsfqi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtpbqzhdcf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtfufzoddm.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtscwjskyj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtoemzzzfx.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhsazire.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtqxujsxqf.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtpmtpspan.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtzjtncuof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtqzumuvhw.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtxnrtrtsv.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtojevghii.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gticvlwdcj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtonlwkvea.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtkgpjcmzx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtgdvcestm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtbpzzunsl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtkdefocsg.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtgrrlrevi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtoxmwiwse.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtnxsretmn.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gthuwmlvoc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtchqrzpzr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtqrylxmts.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gteqsqwely.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gttjcddzlg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtltopgebb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtsjffmbal.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtkmclnkfo.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtcrneoydi.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtxnpybksa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtrmblhvsf.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtfdbwpqus.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gttmzxahjv.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtorpurwee.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtctzvwlna.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gttltzuiwx.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtkhjjvfvc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtwftyfjau.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtkglzrszx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtlbdxapfd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtiacoocgr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtxjkcwxgy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtupagtoin.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtnfxdbpbs.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbsigqxy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtpmszto.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtzofkacor.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtkkksgitr.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtrntddley.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdnviwsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtfwrwgxpr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtkjayrfpg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtffaxyrvf.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtoyusywob.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtenjcglko.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtjrrlizxe.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtrnzbvfkj.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtlwpljyrp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gthqvsrpkz.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgedbjkwz.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtgqifunbl.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtzgoajsqr.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtnecfqudm.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtflrempjr.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtwnnwhinr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtlnhwymam.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtonapmkcq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtodwahivf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtknsrqvon.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtzwfrgnmj.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtraksvhsc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtqnpfebmm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtagwsazpq.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtwwkpjuan.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtgvoxbjmi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtjfjcnlye.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gttazbobjv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtmanomyod.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gthayenecp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gtpsbytott.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtqsymbemi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtcxrjmkqh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtolqqlrsw.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtsqycappl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtxmqhrksd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtgyewynji.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtvzlpfvzq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtgwowjvbv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtwppwcazx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtpolmneav.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtpqrsficg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtbmkwvrtm.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gtyatzpkmu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtvccegrtv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtjinhgaoe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtfcvlrgfw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtuelzcbue.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtzrnwsetc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtkuuntgtu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtuqdeqoqn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtkrzkekll.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnvclnxvz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtditygkco.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gtxqpnfspz.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtopzdeels.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtrouaiiul.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtnkmjggjq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtscwkrmdg.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtiziugmjv.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtjubnzmlu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjivrlznt.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtberjgbuw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttumcgxsg.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtkezjhstx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtjjmvykim.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtdrkapqak.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gteyozhwfr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtyilioaqi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtpdtsrkvi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtkjsdwxjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtazaptree.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtrxvrbzux.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtluaqwmfs.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtjsvhadhk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtqkyrowxj.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtttxmrbrq.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtwvmetacp.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqqrmiqm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtjlekoosb.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtgtlesdvz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtuvbrerqs.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtgcxqgamt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtesoaxqqj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtfrheumxq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtggnqzawg.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtmugxgpye.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtvgvyarmi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtrmhkcevw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtlvzibjoc.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtbtlrktmc.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtrcofkdri.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtzlniqodp.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtrvdaimoh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlcypcaq.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtidwhdjfw.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtyymdfjjd.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtwxgefgyt.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtmepgoaer.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtfnknqrbj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gttqbexhfj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtkwvmbiej.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtwrdkcyab.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtxvoaymyv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtotwkmorc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtxznlcvrb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtljkdkizr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gtuzcdfwek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gttonzxlrf.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gttchnesid.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtifwmztfu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtvoprrqha.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtkhdwhbkv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtumrrekgt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtbvtzpcbh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtgxipnlsq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gttkqlvubc.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoaqzbri.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtcnvlqxhw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxinzvqf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtnzkkexmc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtwsyvdbfh.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtmqmforzd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtxzkbhyga.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gtssgwkxgq.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtyxdjnjts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtwgpvekpa.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtunaodpnq.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtfqrzpjln.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtkbhdoath.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtbdawloim.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtqgsdapcv.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtdhqkfcem.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtpuqyviea.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtbcigdmqg.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gthfhjcjnt.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gtpfcxalok.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdnwiivb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtstddycyx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtqntsfsqi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtbjhtuvfj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtfmqiydlg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtnrmwtysu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtssaicikj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtcuzosbtb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtvfepwdmo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwvtxgqb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtilmjmspo.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtfnrlbltd.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtjfxzubfm.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtzbsrpprz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtiyprxajd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtrfhlmkbj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtyvrgbjwr.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtdhupnmua.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtcpulijug.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtsndbqcge.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtvzcliqlu.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtqbgijbeu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtftotcfmb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtklmbypvd.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtycqgcljm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtwbfumuoj.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtwrslgekk.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtaguskjqh.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtacpnfsqt.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtzjrvhjbf.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtfqkllxjj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtcqiacchd.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gttxlzjios.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthytkuoou.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtyaunkiuc.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtsxqvhaza.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtjfdubhej.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtwkmpgcdo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtutmigfcy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtvozxuwsm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtimjuhqif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtvutcfbyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtirynaiul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtdzvcxkua.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtstdbkjum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtoyorkama.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtredvpjhr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gthfsyegzy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtiolzdlrd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtpajqjeqm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtysihqdys.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtobxwwkbk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gthohrfwgi.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gthjuttcjd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtyjzncguq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtmiovvvpi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtykpzrhtc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtwczutlum.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtpvsojcky.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gteupizpji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtddyskqko.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtypzljgur.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtsgfxizvg.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtinlpxasj.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtpiznrxav.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtcewjjzkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtpwxwbpcj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyssmcsi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gteqifaiie.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtygldqbyq.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtuegezwqz.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtcsjawmcb.html


<!-- 参考信息 -->