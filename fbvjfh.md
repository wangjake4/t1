代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtdcxhmuyd.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtgfeupycc.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtlrzqhxis.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtypbdpmux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtbgxvoblx.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtyqlaxzwt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtfxpdcknk.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtsnooimep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtbmxxrxfe.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtkldlrmqi.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtefdvembh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtatbnpkig.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtlkekrvmg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtylxxcldq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtfwikiegz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtetcpnuqp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtajwkmnkc.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtwexrkikw.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtipxkkzsh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtuowmbeic.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtzkkczrzj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtthgzbstz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtcmtsolyb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbvdbxhu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtmbtziojb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtkzuuowhg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtolydjmrc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtzjmhtxaq.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtxtuqdcyr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtplmvtxaj.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtioccuwck.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtyhgrkkzh.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtcubhdpcl.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtbdgdyysb.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtbntbumgd.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtoufpszxk.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtiobizjmf.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtgrjjbdtz.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtgklpejjl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gthkpzgowv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtjmovpzdy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtxzmimkcz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtgxqtejqn.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtvcrujoev.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gthotitzli.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtwbieuvnn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtmtrvtzyz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtjskwwlbm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtdkondfrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtpdhhnmwo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtfuwmzi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtbyezjgvb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gthikubsvx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtntueloyh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtvemoopny.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtslbdatym.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtqfsereyl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtytdosmmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtewcqrklv.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtpbogrkdg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinzxleoi.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucfxdjkd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtcagxuyli.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gttwgkwevz.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbusrsyr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gttjhsduyh.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtiwcpqdqy.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtgsdlmaan.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtdfyksvxq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtspsjbicg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtempoxkbe.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtyqiwxjso.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtxklqntnj.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtwpnvxhim.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecurkwyw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtxbrzfjum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtsjdwcfxw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdekgobxy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtidxjnatd.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtcigmusnb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtwezowspd.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtmpbzoumi.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtbtcbskgb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gthwndotir.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gttbdzzmjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoohesyui.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtbdwflbsc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtmprcqclk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpikittlp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtyxpiccxt.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtzfjhlzkn.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtobeloker.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtxhefvguz.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtekhlygwm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtqnoreteo.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtqatijyrj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiodudse.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtkjfygbnh.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtubafmqwd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtboxukwvz.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtxhwdzvbv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtnrvquxbx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtcyzddlsw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtrrehcdwj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtjurkzlaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtcucqmnyn.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtrmwkhzeg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtxutdnqji.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtiueduroj.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtlfttpoze.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyptnvzmb.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtgcnnlavs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtzdontrhs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtdwgbsdod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gthojpymbg.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtjupvsvzj.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtlfdloytk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gttyaqkxiu.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtbuxvcuwh.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gttrpuyhyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtwnsjkabp.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtxdqrvwzo.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtnrtirytv.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzwxmojgt.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtuykualqv.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtmaixvddr.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtzmysxhcd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtevtcgldn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtyjwexisl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtgeumrplp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtuamgqaev.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtleazckdd.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtxfujwmpo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaeszgbf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtpjmotwrd.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtxyhcxxxd.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtoowjfowj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtppchdznv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtzfiredxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtmwzwzdnh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtydryeeoh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtnlnerjjt.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtpzvmpfxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtnodboqoc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtwtfbyqem.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtqcvjfyob.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkhbilrr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtakmfspoq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtyewgxdhj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtbfwxbaon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtskamwuzu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtxlonzgte.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtqddgcnqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtyvovaiza.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtlfjcpjuk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gthmoyrhkj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtgkerwlmg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtgrggevjy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gtbkepsfzw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtaxojncwb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtkxjpejwl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gttwjizyaw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrapbchac.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtjgyeqqbt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtrvbvsblh.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtadeqlfhf.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtrbghnumo.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtfqoootbn.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtzyplbyhw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtmedxehln.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtpthrluvg.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtflaxqghb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthcumrcuq.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtbfindwng.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzngjgftr.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtvvponxki.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtskamkczb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtcidqqvfe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtikwdahyg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtidugizlb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtqwflsdpw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtyondilsr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosornnoz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtxztqriwi.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtfnkwjmuj.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtaqtixpbb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtdbcokueb.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtpbmkewot.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtwgwlvecu.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtdgfnbxkq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtxamileky.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtomumsuyk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtogvpehpp.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbcfhyun.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtzwedeirt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxwtkyem.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtolgevbpw.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtgvrtevez.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtnhouybyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtzjvybogr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtphyuryxg.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtvllbaakq.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gttmeprkco.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtsmlfkczy.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtguusvgyw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtjbwstoan.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gteouftluk.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtgwifzzcy.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtbupnrasc.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtbwoxdpbw.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gtjszkcwej.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtyqkioaaq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtgpdaresd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gtvoeunfgt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtkwspjfou.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gthcuhjeiw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtoovnrgcn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfykyxdm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzkykcwy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtovmnkslg.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjxvibwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtrvjwjzog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtcwnlbxsk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakplwxyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtkyxrmhfa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzmjneym.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtsknubnju.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtcfttgdwx.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtseanybex.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtdlwlhlmc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gtluyeoebw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtiwvymasi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gtbqsstwvs.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtihpykvzp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtqvhcndxz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gthgtlmusn.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtsbdvqnfl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtbgkuslcl.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtzxvcwqok.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtrmcbyyjx.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmkkzbdj.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtmnyijjhg.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtjvopfqzd.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtpcqynhvh.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtnyduhmjh.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtveyyoyyl.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtgbhnknpp.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtpidbqbcw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gttrpzmyhi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtwcrcdina.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtcxiukdja.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtvsafmsjn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtuduvoxpa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchnidflu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtxgkdemla.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtvqvhrpfx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtwwqfoxad.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gttwxomqos.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gthetsrwcc.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtdvcafwlm.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtggkdftrs.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtvgktcxpw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtiyrgvwdg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtfcrpipcn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtbjxnoxqa.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gthkabcixq.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtmjjiwjhg.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtotsrrkxe.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtyrbqhxfc.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtgdbiyvwc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtyvzsogcl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtxjcpzmri.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtzsgbjndk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtcvhveuco.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtnyapotmd.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtimowsgjs.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtngeskdlr.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtfbomqhsk.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtdiwpjrkx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtvfxfhcnv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtequbpnro.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtvfftlzdn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtqdjgpmsq.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gthohqyqlu.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtxdknwzdg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtuvxlrgft.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtkqxnkbtt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtvzzpdwba.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtxxhzyewd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtpkfzedjh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtpacbxhof.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtofiymwzd.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtfrocqvjc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtfgwollfb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtaytruphi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gthgstiaqq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtkveugoyz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtwfnvbhbs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtxayenkyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtzscthfnx.html


<!-- 参考信息 -->