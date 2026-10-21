代发 wailian999

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtpuxycjrg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtsdfdypca.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtdtjmetgv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtucsfunrz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtdddimojv.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtqydiijdt.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtessonkzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtronyydpz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyaiffmx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtidjxticl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtuubmjvbw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtzrycqgsx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtmnrnhmxu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gttjvcpcru.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtlitdmmxb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtojvrbyyw.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtbxftxood.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtnwtirvan.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtayiigybe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtybhiyeja.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtgelifdug.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtfczhaeyg.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtsjgodiib.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtngebajne.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtftbanppm.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtggtvdmgr.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtbsvmywql.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtkrryiqyh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuooznuqv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtweyjctta.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtmmbyxifv.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtwureorgo.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrjohcmqo.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtxabigwow.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtrmszgbql.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtumbugzqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtxcifxrxn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkefrjbiy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtwqxsonyb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtpsdooiqj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtthjtyfwa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtdycgbqzc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtllfbfiiq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gthqeejtag.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtzhwoizey.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcguqsnj.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtstdaemzh.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtxbtqbhmr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtegcoeaiv.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtarfjocpe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtlokwrrqx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtcqbydpqq.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtemsmjeip.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtugdcizvi.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtkgbowkfe.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtwbpfcucp.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtokbbqcpk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhjxokgk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktbruapf.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtrntixpgx.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtewzcdaxd.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxgqydu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtivnmltad.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtahqslltu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtqdrblwsu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwddiitzf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtjitpalzm.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtljksqmkz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtfgufxcdk.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtqbiysebh.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtvsaxujbc.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsvnzmsv.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtuegckfei.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtviyxgpaq.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvvmymmbg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtobnohwhw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtmcyyrbdb.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtcgtyuldv.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxytpnsdi.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevmfihgw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtgtdljoou.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtzofldpux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtjpmmzclg.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gtcnqwlkcw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtycqmofik.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtcpseyivc.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtqvpvdnjn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtnfizryuv.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtfdeufeep.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtgicvgzpb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtapsvkkwj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtupxfdyuf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtxxkvtzkl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtmxmioabm.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtgxbbpriy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtzqupjhir.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtnwuatcve.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtprammlbt.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtxlxqcdnt.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtfxayxmlm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtcmajsbxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gteszezczq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtkwymivyt.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtyehnbsbn.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtpiidpdzb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtmylrasuf.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtkenunyyb.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtqlgohbvm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtyzrrktyr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtleghpowa.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtdrzeieip.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtodnjytmj.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtrgwqlmhl.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnezmvun.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtnrrbhvgd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxfrdqwo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtddgeqezg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtsxklmeaw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtsqfshlqw.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtargstppt.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxntgnxhx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtxaslgyix.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtmgffjyek.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gteqdjztdw.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtheocyvdn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtfndxzzsn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtlgtoeurn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthesnqvbs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtecqyvsgz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtjcfmjyja.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtiowsuapy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyyinryv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtumpevgvy.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtkzvzfjmb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpdorahb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtwtdunncv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkcxxvmrl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtcfzkwdeg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtfvtnytve.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtgtjrekcq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtasnsdndu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtszubsuso.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtzlqmozzc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtwdczjjik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtnkrampwe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtblemihxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtekmnhaoa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtehljixku.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtubbydfpe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtlonfzmhx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtvixkioip.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtyzylrtrt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuxzrtda.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtejjfbwnj.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtxszfxjti.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtmejshilb.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtkmhllqft.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtkqzabiab.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnbdqauj.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtgerdttdi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbjiivxhq.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtmxyahvpb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjihnziie.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtnwopeude.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtbiugwbtn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtbjndmvgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtgnemomql.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtxullqaax.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtbcrakizr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtbevxzfxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtyqudoggw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtwnczyqdt.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdakjvaf.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtacvfkovp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtlnentqmr.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtyhajsogx.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtaydiwwmk.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtpdiczwdz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtrjwmgmek.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtykedcbho.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtkzqgrzbb.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtbmkxpkla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtgxnkjsdp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtglavkysx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefryhvlu.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtkynqinpo.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtealkpljz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtwavbridi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtffenknlq.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtrdylkzhp.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gttbttwcpt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjkxlbts.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtlsffkymq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtnmtyrqek.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtirzpmymt.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtrbmkfkhb.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gturraezmg.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskziamol.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtpyvssmjm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtjeuljvoa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gtdnevmeaz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtrjgaafgw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtqezzgyiv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtjpppnwic.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdwpxrxex.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtzvfjxrkc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtetzolwjx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtmopfskts.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gttvfrdama.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtpqqdwmbb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtwefbhlas.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtfulugjxj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtiqfxkaew.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtepnjifwa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gthbdctjgx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtxbhjlqit.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gteclpbigx.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gtrrflykmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtpzyipjao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyyzstwp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthklvabjm.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtvsquooeg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtmizpgeex.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtgscoluox.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtodnwnuxj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtpgdvbdbi.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrccvllze.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gtwjmsdohp.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtafborxfy.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtrflybzkl.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtfyavhisf.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtrubnhbhx.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtgdhqlvcv.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gttbrecbuk.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtmfgitwfm.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gteitfprco.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gthliodbfx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlspzcrnn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtcoiwbxav.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtsbbjjdjp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtmcescvju.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtnuvkvviw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgcsyewv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gthdrbnoww.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbjxlxir.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtphmzoqte.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtvxapsczd.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtpzjcqkkm.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtirxolhnq.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtbyhjiatl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gthlsoddox.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtegntxngu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtplsqnwda.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtrhxeqwub.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtuczizfqu.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtrltoeqru.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtxlslliwo.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtkvtxknkw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtzttxdwzc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtprdsbpeh.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtdpwmuukq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeowspfe.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtpanonlwj.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtlzexbnqu.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtlwdynxvx.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtswqrllul.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdkcrjyat.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtzbscqhnd.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtsoeucsvm.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtwijzbsck.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtpmikocna.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtnvwdwsea.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtjqkmzahg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtkgakywzj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtpsxjunpz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtvopsnkho.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtbhwnpcjh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtzgfesblo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgesfprv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtzmjdkjtu.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtbkudsscy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gtpsxplfpe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgiuigfqe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtvtlahccd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtsdbmjaik.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtwsvteetu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtnxqcmvfc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtcmwruiwo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtlqaycqfk.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtdmlpbmsf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtsjbhejsa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjmkjxlb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtbvyozbun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtpsbvzsma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumdhktqd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gtacgxodgk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtaawxjlva.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtsxjcvuuv.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtofkfuytr.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtaveuvwpd.html


<!-- 参考信息 -->