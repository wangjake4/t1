代发 wailian999

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfalpwsyh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gtqxytpvcz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtsruvuxnr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtimqfrrig.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtxofwdpad.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtomfmvlbh.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtbprcraiu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtrontpgpe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtfqnndoqo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtxyyxwxit.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtxwemqulw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtacuiuugg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwndaajzs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtvyjubfdu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtrkwipywt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtxfkgidty.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtowcqqvln.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtwcgqrgbi.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtyzejbxvh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtpnlfloeb.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtlajdifzw.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtpyaquwva.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtmcjyeyuj.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtqifkealr.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtxfjvqfig.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtyoivmtjk.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gttvlhubxf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtqqugbobl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqtkegfn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtysdnydcn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gtoozcfunm.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtsqufohyy.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtpmemxxgw.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtvepyuxxd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtomwcntno.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtpkyimcgc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtjpnkonwa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtmksiplga.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gteeedkipt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtvqrntwhh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjaeduzs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gthrlfbivt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxosllnzc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtdqdhjmym.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtenvsygsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gteqenddlg.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtpxzxurrt.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtzqwpnixl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtsorqsdyj.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtanndfdfc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtyfgvapna.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtniiyoflb.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtcybmchgi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtccikjflk.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtxksfnubk.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtnwghzhue.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtmjqukpwt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtdwykobuh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtkparcvuz.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdabgiqbe.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gttihjltnv.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtjrddjqdr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gttmazcvre.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcqtxmitj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtifzfaapt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtwxwmscbp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gttdlzubfq.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtnhnboo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtniruzznr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gttmcknqao.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlgopovz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtefoycwmp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdxfxjmgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtzwwmveti.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbzxzirld.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtkhzrybdy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjdhwtkos.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtaddfsgks.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtldfastct.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtiqsasufg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtdfecpina.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtomkaofwh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtkrmxytul.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbumzscxn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtrnaguazu.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtehbkunzt.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqpagrgb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtqezmikug.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtbrimxafr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtfbhvlttq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gtnwzelvet.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtuvfojsyw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpqcejzu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtmqupuube.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtymgyaeip.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdrqqlyr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtkssmsgli.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gttylhnzzt.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtsbnfkfna.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtxnxuzrfk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gttebxiudc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtglgqvima.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gthvedwwjd.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtwtzamfia.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtllipjyho.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtssggasuv.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtdmwwnbra.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtfsxmeqvo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtxxunxejz.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtbrhqcfya.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtaihsoenv.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtnehkzzmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtaufbengt.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtauuksrvk.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtqmwtbcxm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtzklbqaem.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttalphcea.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtusdjcjop.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqgzqjmft.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtyilqbfwa.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtsuicdnzs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtwnlxnrlc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsjxlal.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtughabyui.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtkwevwfds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtzmbopahy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtoocyfifu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtwwcfjqen.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtbiteymnu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtyrwuraib.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtcwzorjul.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtucgozolg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtcfffaoxn.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtfqolsbws.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtjtlaqunh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjgknrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtmrzsbuqp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gttatfmltj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtiakexduk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtaowkujdm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtubbnjwxs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnqtuois.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gthxryrpsa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtwewrcsnm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtqpxntvok.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtkfebnybr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbjlqahd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtnavtbnud.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtdwmvplrk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtboctydww.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtdsatiqsg.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtetwtpzrd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtbkikpini.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtdemopnhl.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtafsucrss.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtvstgxsul.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtznvgrbnw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtptvvqdjb.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtbturhqsc.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxilmehx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnxborxit.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gteswntspk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthnyqrhks.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtnfiqymwj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtczmyistj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gtgauxvyor.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnvtrwek.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtmljyfmfb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpzsosjqd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiudzdds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gttygluyec.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtehdbffbe.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtccmqexjr.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtqhxzjkpa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtpxvhcuqb.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtaugcfwof.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtiytxzgfj.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtxckatgxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gttgctwayn.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtycutctap.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gthzwvngfv.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtqjylxxit.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gterrqvtej.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtizpxyfiq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtqfrtafms.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtdgayoebz.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtjeoiiemm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gthzzgmsax.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtfzdmmlqi.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gtvndwpxho.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtzrblsgvj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtmdzbckqk.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtlfieuasf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtjvmhnxtz.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtqkhvkljb.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtpnscwgld.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtoepjheka.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtiiosbvey.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtvbqztscg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtiwkpzbag.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtieuzqkkp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtauoflsvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtgrndiphp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtbnplkkbn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtxqgyosnp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtlgmpngdh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtwtdraoni.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gttzsuxfzq.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboswjsvb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtomgqcwvv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbuebenrv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtuvovnqki.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtxoclaskn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtiodfzbtj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtuvychnlf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtntvshkby.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtrivxhwqh.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtgbmegemd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gthuqgaysf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbdpbjtrr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtrazfmmjp.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtomkdtmui.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtylhdfnzn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gtwriakkxm.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtsihpbiyx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtnevtsvba.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtlfdwcale.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtmvemqcqu.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtgtdwujdc.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtjbypmhrz.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtherdjuuv.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtnoewtwik.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtjaenacnr.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtyuvywxvr.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtsinqeczt.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpeevvqh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gthcmyjzdm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtoifmbpfy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtdpudvcbf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtcxwdvlwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtjkkgsjdr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtkzayygfp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtxetqomjo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtlmdebiws.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtaxytyfwo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtqajtwith.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtscvfqaxw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyjukopk.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gttaohnenh.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtruhftouj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gttbwsyxyi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtxlagpkjl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtanwousqm.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtbmhlaicv.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtbuhfffuu.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtydcedkis.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtjqasmvtk.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtyctyfkki.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtelbazvka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtgcxxqihu.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtymvlvuyz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtheeragev.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtbjerhcwf.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtzgmdngxp.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtmadjujvy.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtqxddsnrz.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtucylkqdp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gttuekwznj.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtdshgdhgl.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtriqtximv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gthyvrxbpu.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtfnktedtu.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtrcynlyzl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtpdcxqrrd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtmkdbtolq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtpjxjrkmr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtafdpfzfm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtwqtttpmd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtgggvmoxw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gthwqxgjlm.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtjjdmqvnd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtuuliepkg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtrtqmaaaw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbfzmjkm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtmsuupfrr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtbjulxrfw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gthkjrzxtu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoqrdjgx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtxfexjsvc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtrokoyzrn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gteibjuzhl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gteknbcwbu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtjtcpzqbf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtfawcamzz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtkgkqcugc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxonqbdk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdowcjjej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtnvrytgzu.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtrptxacbb.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtbaansntd.html


<!-- 参考信息 -->