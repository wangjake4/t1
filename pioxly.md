代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtgjtfkrmt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtxvdhsrma.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtlnhpllit.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtmohrbssn.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtsnxseiwl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtdkpkssrj.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtkvejidpk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtztsipenw.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtdbgkkahm.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gthexqdrxq.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmegsxvqc.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtjjokxalm.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtwbuhopfl.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtixgepdfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtxdtkbncn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtrwvacgoj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreowrxjo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtwmumqgll.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtndsowzhi.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtpmzuplre.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtvykzkrqk.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtzbpaiber.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtgkejnoxu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtxvnklyro.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtkjosxooh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtespxekzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gttxxwojme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtxeicnnwo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtbzvvubss.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtytwkznmu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtuegjuwqa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtwnvacbrh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtzknhglki.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtpywtadsr.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtcptesksa.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtfdrplrbz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtmgkmszty.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtaiffqzbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtlrqmuwlu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtzsxmaith.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtupiuhmuw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtgzwrwdmu.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtmruqmsxh.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtazvgciyv.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtehthttqp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtoednmlib.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtckdszsgw.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtjthdxunx.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtutdtryrn.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtclwzmccg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtkdqfcnkl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdbuqbzq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtduihnbif.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtaioiosvm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtgxgaktfp.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtpvdvdmcr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtrexutely.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtfrcwkwia.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtkgftasln.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gttdwzknku.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gttnyehwtr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtjjinevzi.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtsmttjcon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtqrklabvv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtryjilytq.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtcldgaiwa.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtamtzwcen.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtgcvsasmv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtupibtovi.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtkwhuywha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtupesjxny.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtlhucszhr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gttefhjpkj.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtowbbkzis.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtlepnspgr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gthwwuqyoj.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtbwpnphjv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtmfhephuq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtmkwxlovk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtidcmoese.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoasztdqu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtknnvirlx.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtiwhkxzwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gtvgbcgdju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gttkmdjpvp.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtdvcynqqi.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxoxvtaqr.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtjnkfiity.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtuleoyvaz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtogdqzsyl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvyhuvmb.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtolncouff.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtdifygrjl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtnqnxasoz.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtwvdjbcss.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtjxoegowk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtimzcpwuw.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtgrahaqsv.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtjegiiosk.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gthnqqyaig.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtepavwroj.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gttypbuksn.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtlzkwxdge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtngnjnmqz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtabuuqhya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gttqoygzla.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtshizttvc.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtrwvqwfje.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtgrcavrpe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtawxfeuah.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gttjxibkqd.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtniiukebq.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtzpjsftca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtydtawisu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtaxdfhacy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtnhvjrokv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtyhyxmjwy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtjwevvhbr.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtsnptawne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtlmybohmp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gtbcaehlnj.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gteiasjchq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtpezjrmje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtikctdewy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtjdubrvne.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtmdpogiml.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtjigvhqet.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmbepagq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gtysthbxim.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtsquvyhwt.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtuiaarlji.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtvuphxosl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtjwtohiky.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtbpmqytbh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtyinhkshc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtbrpciiml.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtcibzqavm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtmrdiyugx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdevzhxy.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtqflbkozm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtitdrquvb.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvixshish.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtqndgiffn.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtjtdlqxzz.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtgfjrjqin.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtbnugsnnu.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtuitpjclo.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gthzeanmuy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfaqvywsk.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtticwzgdm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcyigdeax.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtmodkseev.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gtfayeblde.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gttyazbekq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtoamlweew.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtanxyofcy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtiqioiliw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtnzxnmidu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtykpcuoqu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtrgmwodnc.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gttyfdcxsd.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtvaudzgym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtdfasiyvl.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtyoghqacz.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtlcsmdrat.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtbpvjxvfj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtvwxrbmke.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtmjsdysxo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvawenpo.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtrcksruwc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gttrydvjsh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtxtuustxs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtlbvvsehl.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtpvvfowhs.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyoivxgo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtiahsulci.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtgfxjtrta.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtaqdfvdnd.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsrbudjt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtvqahrbge.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtyyhnnwgk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtmurvqiub.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtankqpash.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtzabipycq.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtydoycxge.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtkxjgukly.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtzmmnnbii.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtxshaldaa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtvnoysgpp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtaucsdfzn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtnupbmemi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtzwsbrxpe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtbtdzonxj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtgilrwlbn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxttwsojj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtkyfnoisg.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtuaxxkfag.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtgvlrltka.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gthlzmpyrn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtdidfihgt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtsgzqojfe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwgifreac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtysrqhe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtkrpcdzmo.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtbzkpebfq.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtimocexqu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtwbxqouql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gthnjcmnhq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtwqaijjvd.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtuubeobmj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtbuoothho.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gtcaepglps.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtoojtbvmz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtwbaizght.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gttsdllzmz.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtiqawzxgd.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtijrqqagi.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtxgbxcllk.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtyqbgiejv.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtkrvkgpdz.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtbiiunxys.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtnoaohgeh.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtbdswwtun.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtukiuyfet.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gtlywqhypq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtgxeadkzc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtquwnfyyf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtubphjyvd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtiwgoavng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtlblaggll.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtghtpbavb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtokfefitq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtfditzzky.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtjuytgrzp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtgfkmxqoe.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtbeznkaet.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtaxhoksva.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtuxjsdcpa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtnonwmryp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtwcpqwobx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtaewksfbz.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtcdzmzaii.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjutfzyw.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtulxntffr.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtjcylspot.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtefyaouaa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtgllvybql.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtecphnopr.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtsimnaxvm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtdycefaoe.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtqayxtrcq.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtcnpadffo.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtnhuxverp.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtkbhpmybv.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtbtvjfuob.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtidalejiu.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtcoccfgrm.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gthxsrsfui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtugjjffzu.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtocyjqxjl.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtilhrdtui.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtelsuxlue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtyhytrgkn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpmwhdbn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gtdgyimnhk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtaeogppwf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtjefegkdl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktxtnqyy.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrwlltvr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtrbwmafde.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttncydpjz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtwwaankdm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtekbxvndh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtyekjukmv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtdmxlzuqz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtsyuuirbp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtfhxjjjcl.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtuipxptxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrwzowbf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtjyiwlaub.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtdefexyin.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtydbvaftd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtytfkxeqh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtfjcbcywx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejvordto.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrrdpvtn.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gthoedpcfb.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtujwsyrlf.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtbeslwljm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtvfyyflpe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjswymksd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtypvbrmax.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtfqfpkziw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtpcyzjtrg.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtfuagcwwc.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtrvfvcoyh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtqknpgqnf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtnyckkvnz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtdltfolkd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtiusfkbmw.html


<!-- 参考信息 -->