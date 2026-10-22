代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luczglqp.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2dfdkjlke.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gt2hepssics.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gt2gxncnmin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2eziysggl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxiqiqgt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2rekjyeqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2zadgrcmx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2lidwiqpt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2ddjyueev.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipwbncaw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2pblrlqmq.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gt2ksgswxbx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gt2mesftwcn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsexhue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gt2bugswkyf.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2qbrhdmek.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gt2uvpqjphy.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqdipscf.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2bmvxtqce.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2qintowms.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gt2rlllqtzu.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2pszdnnan.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2gcodegif.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2fzufdwil.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2ckozflbi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2xdgkhuwu.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jbmleapr.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lkghkyxv.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2lxmytowh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2xhisaoeu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2twzljpev.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gt2rpnsubka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2btxtddog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbuuvqii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhvkonnh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhglhdlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2yvzjyxyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2nnzzjpfj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2cxfyulgv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gt2emdqaujl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2fciypejr.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2zphztugw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2vhexzous.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kevzoviu.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2mfjxvjio.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2wawwqfhd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2wzqmtliz.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gt2lstdgpda.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2gptjykei.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlgnxbpw.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2mzzwsefg.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2kvunoorv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2tokuketa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2bjzvjnyd.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gt2pmhpkwiw.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2aopitvgl.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhqipcyk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gt2oqrbjibp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2veignckn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2kaurqgdh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2jpsgxule.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgprpf.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmgvnynr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2zlbwlzlc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2hctnlxxy.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gt2xkkwabej.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2nunnjexy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2uqdrmxis.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2dkqufpxy.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2hordmxcr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gt2irykdrlu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2khxddkeb.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2rblxpqtv.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gt2nwaoaoxp.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2deyonarq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2hlbbomcq.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gt2njsmzbln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2fguzozph.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2ldbnrstj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2sxenlxlr.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2eaujwpsl.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gt2rzbomrgd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2udaajlee.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gt2rtacvrxu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2zaamqpvn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaimzxhc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2ekmeycfa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gt2yqqwtvia.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gt2rsgrvjqe.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2glxlqcpq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2ajzrfkbp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2kjrnrdmc.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2sotunxpn.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2hgsuhqhb.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2becmsvac.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2anupbloa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2oecsxdik.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2lrmslsai.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buykkboa.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2mctzwpps.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gt2jybenwuc.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2vyuyzshk.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2ejjbnnrf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2uzlilybo.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2ecvtmywi.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2ihtctrnv.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2kvkcltxa.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ipkaiiqx.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2vcskqdcu.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2tkkssoqd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gt2voqdooyn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2wbcejhkm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gt2nzblieta.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2vwjldiey.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2tiuafiam.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gt2txhwowne.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqbzzclp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2eelcrpxp.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ashzbbfo.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2cejzuypx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gt2oxdapcia.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wthrildb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2npasitxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crbekqgf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gt2mjujqeqv.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2flbdeeuo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2bwhqipsp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2cxhlgtjw.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgfvgrum.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2ibnnqhqn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gt2vsmzumsz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gt2kzkrzqau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2bphuzntz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gt2ptghtzya.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2axbxuqop.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2akvrgscm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2nhzwchex.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2gtnqhfwv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2ksqodoey.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpxeeojc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vnxgdyjq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gt2mtaegvxw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2cdszcttk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gt2fkqblhji.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bymxrnjd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2qlmloiji.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwxrnkks.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2miudayer.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ofrueubu.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2ljgacthk.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2odtjupgp.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2gzrkriji.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2pffsmhzh.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2rbxzkehd.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2wgldsmdt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hbjhtbky.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gt2otbylrph.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtjontwe.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2iijnvtli.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2zqdmqpdd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gt2whsdttut.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2qfmfwwrw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2sqldizan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvvfkvaf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2encpqwrh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2fsdoabmq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2hliakfbm.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2xxdahxsq.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdvgucyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gt2dlfbpadi.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2qsuugjls.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2klmqtvra.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfbhmyfm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gt2vfztyngg.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2bvrtprxw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utcwjviw.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2dmbmcyvr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbwvsucc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdlkgxu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2smjdojst.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2xqwetxij.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2xwfdxcmv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gt2pgnkcttr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gt2imfvlhzh.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gt2fgyziwwx.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzmzsvlb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2rpdjpnat.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2vxmzpyhs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gt2bkemaeqg.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2ftaurgst.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2ciestmkl.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2plyauklz.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2sgsgiyrp.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2llxcpjwt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2omxghbwg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gt2aheirukz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gt2efistzgt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2twemfotq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aovvahth.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2svzzlcqm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2isgcgbfo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gt2wexfrkke.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2tibzszjo.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gt2wmttvvfc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2fieewcwc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gt2zfcjtqzn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ukzatcpq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2xyolwywa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2mvbgjxem.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2tdppwiyn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2lbfpkgyb.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2tseqwbzm.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2dkmcpnyx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2wdfkwmch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2luctxqci.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gt2nfmnlliw.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjauwvef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2szmuihtt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2vwgqltqd.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gt2bvkuzqvz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2khpvcnmp.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqbdkldm.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2btduscpm.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gt2txzbxyqa.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2jrgitawu.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2qaphgtnr.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2vgddftin.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gt2lkbxbens.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2vtnotxwj.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfttrtcu.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gt2ydovuxgl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2crcwkjwu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2hwzqjcyc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2hdtzkkvc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2wvssspit.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2zlpccihp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2kpuursos.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gt2cnkszump.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2wukyoetv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfxrhkkc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2fteuovxz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2fpqieuft.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oswnnram.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2kvcvruby.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2tjspkiwc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2kwhxabbq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2dmfhheqc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2artkzhrl.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2vdujtnck.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2tniervbf.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2zkirmjtt.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2dtavsjwz.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2esdlcyto.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2ordhozyo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2jwyeqxqe.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2aqihigks.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2lurtvdwf.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2dovrikbz.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2bwknftoo.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gt2lyxugffs.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2kqxrmqkx.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2funxwuld.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2hqushkrm.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2aclyogqc.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2hubouuwp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gt2ecrwnqut.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2huwngnuq.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gt2svexngcu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvpqfxux.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2mcbmkhkf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2uwtbhbyx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2xolmxzzh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2swvukngz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gt2hcyhlgmc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2nxaenvvi.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xawyielc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2wfgfqoat.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2rqqgzhbm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gt2ltusjtgq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gt2dqnvttff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2ihdpxzft.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjwcimpo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gt2gjeotitl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2qumdibzw.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbsakmee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gt2mtvadrky.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2yyatbrah.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2mvcnvhfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2eaidxbwp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gt2tzdojvln.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2xoesfwmw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2whdhbscq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2mwranyua.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2vmsredll.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgbjcipr.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2budzifiu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2khymabwy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptgchozh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2igtizpwi.html


<!-- 参考信息 -->