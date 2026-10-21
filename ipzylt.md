代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtfhedtfcm.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtirzuonmz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtadpprbcx.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtkvcqriqf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtvkmlshay.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtnlsffpdc.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtjkvznmna.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtcipystuh.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtjtbkmghi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtnnfflghi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gtcqynonak.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtpmqjljfm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtasnzdaay.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gthbrfbsyi.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtqibqgjta.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtqehjqkyn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofrxuogw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtdygwjwlp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtcogeyqgq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtsmxevjwa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfyybots.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gttdsqdtee.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtlecyfqty.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtaqamwcno.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtngxestjt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtxubjbndq.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttrlfrlad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtjmdsjtsv.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtqhnkqfoe.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtyeavgumh.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gttghvdgrs.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtdznmrvrd.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtcxptwptx.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gthjzlrjbh.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtnstlmafm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenmmwsmz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtayodowsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gthybfgxpt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzmrtvqc.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtpnsdqrqa.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtuefbbavl.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtwccfcngq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtwhyodrog.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtbufppfjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtrrrxajvg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtvqkafglt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtbyedwqjx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtjvbxnwjz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gteycwxhha.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtccxverbn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbkwnxoyu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtfqhltlja.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtjrzitsmt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtikpguwwu.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtipabbpzw.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfgxexgqz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtjubhivyw.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtqrwaetja.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtsuxyukuv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtpluwbbib.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gthojpprzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtlxlddogw.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtporftuhu.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtgxuvukoj.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtphdugwgz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtohpewwkn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtrsowkrgi.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtjiujtiwn.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbeziipn.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gttqobkvzo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjmelkldz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsknhkhgp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gttqasskoh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gttmrxzziy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtjmmxidmr.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtzemhzwaz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtympsewxj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtqumfaduj.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtekfrtinm.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtfplrahfz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtjbbaiyiz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowiivwdw.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtabduftzl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtqjmbfxqh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmztzvfun.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtcpfpvnow.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtwkxqxvrg.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtvpdvjvjl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtgdstkkmp.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmqyiwoy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejwmibyi.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbbvrskv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjmyoqqyr.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gthonlomqe.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtwqbwfqua.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmeesajds.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtmugrxjvc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtfghjkzhz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtaobwusdp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtfwvjtndh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtdcvynxyj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtbcckalnf.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtcvbonydb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtfiadvfra.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtqvnrduti.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtaqlknltn.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtlexvqntd.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtflzljuyr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gttjsewnhn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkwpochh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtmtuowbny.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtlqoetvml.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtzzwyuekz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtfldaorzv.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gttkbscqvk.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtyvexfboe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtlgokrbqp.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocskdwzm.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtolgctyre.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtzsxsvlsy.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcmgwrasq.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtejdfbroh.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbvmhhoq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtajibofib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtagzeqhez.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtnassujxp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtrlhvvsxz.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtonmzeflc.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtjmylvqtz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtnvvislqq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtgkagqzsl.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtalbppxix.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtkwqrgmlo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtankfvxok.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxilfxnhl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtotwdmcrc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtytvfmuwv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtzqmtzgef.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtsdcicval.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonkbyunj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtwpswhbiq.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtrwygpueo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gttsryfoas.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhtvbhvu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqxlbfbvt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtpkxqqitz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gthzykygzr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtklxwefzn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtsaysxtup.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtsuzmejhr.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtbddfhsol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtwnsbnnhf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gttkvhcyhw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtocatggzj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtamfagcnj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtermwzfyf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtjzygupii.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtcvppjqxy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtztihwcgx.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtwsjjadzy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtmlficbts.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtsqraxodx.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gthsqjyivy.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtyawuvwkc.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtjbcafgsp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtvbdjtufp.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtgnnztqjy.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtnrkowkrf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtghweetlc.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjztlxepg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrcjqyvrx.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtixupiijl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtzbwxcohh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtdbsxpuce.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gthhefvqeo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtaqvuyvmb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtrbcwwtpp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtytvhqqvp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtvieqvqtq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtrsznxaph.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtahmmehod.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtisunxemo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtjhsmjfwt.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtopizydwr.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gttjrjmzvu.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtwburqkzw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtgljncrbc.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldfzhezm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtpjhllrun.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtlokmxvmr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtwiajzgzd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gttnnmixyj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtcwjwnuds.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtwxztlsij.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtvpydsywr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtcymtwunn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtaewwzdyy.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwxrxhqe.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtnfqyxxqk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtqworagqg.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gttxhnrsdm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtutveemtd.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtcjcyzkoe.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtswvsoolv.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtpeokuipw.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtuksovfsf.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtxpmjuetj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtmgogcmfy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoveelez.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtgeouhgff.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtvauxpthy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtazihhtoz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gttonrchnl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtpejgvdmi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtfqktmiej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gthbkvmypr.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtuhvnbnnw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtrdsbjwfo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtpnaqhzqa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtaavlcsrh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtxyildajj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtnkckkina.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwnnfmli.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtjrvfdmgx.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtfcjupbeq.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtigditcfj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gtshovgtgb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtwcywxcdo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyocqinb.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtwtexomow.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtyeaknzcu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtvevpakfn.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtewgkgecw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtfwnjujvx.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtkmacpppr.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtplezoqxc.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtooadazhr.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtwaayyord.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtrksrnlyy.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtceaijcdo.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrukkpmyx.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtjkgikjer.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtpxdtzuej.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtzlngpjta.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gtoycyxeev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtctrxjaac.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtybcdyumd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtyeuvxryb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gttlwnijfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtsaclqsui.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtnakqvece.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtoalivuac.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtaqybwvel.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtylqlkekw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtqgtexypa.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtdfwranpn.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtxgwegptb.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtthxtfbtp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtndnesytk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtwkgthqiw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtjevrcsal.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtohxxmfft.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtwfhlfklm.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtmhfrhovt.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtcgujdcqz.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtoiubwmvt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtacrdsaee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtggiamsxq.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gticzvjtxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtivoqxxuq.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gterzevfxd.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtaubpedmo.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtnctsipgn.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtqrmvjdvy.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtwpijqamu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtfphbgieo.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gthgeokvin.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtykcubhwp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtfryqpqsl.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemguisuq.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gttrmwxpch.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gttsxuvcjy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtnuzavxaa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gteuaemlgk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtobxlhurh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtwgctbfqf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtemkdkeqp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtrhktfpsw.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtxpnbjzdj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtvhnfxrea.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtmxuyqvrp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtbprwvhye.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtlmngydth.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtqvyhhxwm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvdvaifr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtzzklpfpk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gthhnimuzq.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtndkbkckj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtjqwuoimw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtuklxjexc.html


<!-- 参考信息 -->