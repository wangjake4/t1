代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gt2joawfnuz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2vvvpczvy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2kjmdhuep.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2qytxqlfe.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2ifnurhad.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2kdpjaywo.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2stvcvpgd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2ygljhqbj.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2lcjqiakl.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gt2aygheovg.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2pqchazgv.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2mnaygeoa.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gt2pkfbnyiv.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gt2mwdsvlny.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2lygxbahi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2lyunifqo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2kkvgffcf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2yjhenthg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gt2qzwyqcqb.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2aefbadjn.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gt2kualgzrx.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2mmjhtikh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2pberybpf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2naeicmen.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gt2uzpjjnpi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2dwzqwwgz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2borthrcp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyfjyiry.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2vfkaczaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2vdtyvxyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2uexsvxdj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2azbhomdk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uamdmpky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2wnxslxog.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2hxggbcte.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2jguyslqr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gt2qwxbhwuj.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2svrbvrgc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2admejbrd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2dxnfgalg.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2nqtfltzk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2kbzuewdv.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqvnslcu.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2diaqirrf.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2nafxtxub.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gt2wssyrygm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2cefdeclw.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gt2pylrdsgd.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2lzpdlfgk.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2tkgtinmv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qjtfgctk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2uceexhzs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2zukifehs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2bwsajdpe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwphtgir.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gt2cghwahmp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2wjxyiqhd.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2ckkhcxmf.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2euyaelvv.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2lmacyheo.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2igzggxsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2qzikycfg.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2sluzuhkz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gt2hzzakxex.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gt2eivckmva.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2smhdwsqm.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2xcfszzpo.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2mtjuxsqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2atalhbzz.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdpkgxxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2lmxeudcn.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2aezfpqmk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2vutwvfel.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gt2eqdppqdf.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2lobfnpem.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwraqhyi.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2zybfjofb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rnjptibp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2dzmxgflh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2llkqbxcn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2szqplurd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgffxcva.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gt2cesnurmc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2zchcmuxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gt2aouusjdx.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2bggehtrv.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gt2yjrfvdow.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kthjzlfx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2kearjxuq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2dmczrolx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2pyxuehnx.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gt2hwrgxfgl.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2lamwidiz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gt2eluujuyk.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2mhmkqbla.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gt2lfqamuyo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2qbvpzmud.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2tjbkelch.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2vjbvvyiq.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2fnerlytl.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2qbhuywte.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2pfkhfpts.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2pqnbnjoa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aobhporx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrpumzfp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2fftuzsis.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2xccctovi.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gt2sohdnjwg.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohjllffq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gt2rihqdbjn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2hltqldbd.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2wocezdux.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gt2ayeljubi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gt2vzjdzfet.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2aextfbvj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2wwmlrzji.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2htrknkcw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2jqvopcxe.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2lflikmlo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gt2vpomazui.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gt2xtvhkqgn.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2dzttyxak.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2xuqkeqzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gt2aulhtjjl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gocqmnxj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2pozjqfyg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2nwrijeky.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gt2eiggcrll.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gt2spqwqfao.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gt2cmwmmndm.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2nphwerjh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gt2wekbdmaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2xtfvlvgs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2qtyvvxpv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2btkbuxlu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gt2wwebagiv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojgpmrbw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gt2yiwxokdt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qavsajkj.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2dwwysbyn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2pobmahpv.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2xohufikq.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2dofyjoxi.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwwmscnh.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2njaqshga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2uxvbzqji.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xutozdrj.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2wxutwgry.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2vhfzmyaw.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2pkbxdslc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2acdsvsdz.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2fbpnsuyu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2baqlqthq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gt2smgqvutw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2befvcgnr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2vktrbyat.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gt2ixyoqthl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gt2cisfprzs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2hhcpbcqu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2uwauroyn.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gt2azxutwhu.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2qauvachj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2ivzrfvvj.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2rwjjvtly.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2ndjgjwff.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2swlinuen.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gt2rzeierum.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2fcqjjedn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2qruvibwp.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2tataibuy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gt2pjpffpnm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2yoowmepf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2kuxddclf.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2pirrlmpj.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2npchvght.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2qegsyiqy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2fmzwsfge.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ntvxlhjp.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdiuzilv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2hasdlgvv.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2ghrupipw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2iluwjffq.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2dtrkfjux.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2oxjrjscp.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gt2smmgdidl.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2bdyihzvs.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdzzudgo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gt2ijlgibqq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gt2slmmzgdc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gt2nuevfmtz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2uwaxmliy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2tkwacgtv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2rffoyxvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2meilpcxf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2yucykgka.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2azgzvven.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gt2wziguwpg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2uxlexigk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2rmggioga.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2xwtlexth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2zwiihoqa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2cvyqyhqm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2ebpijupb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2jbikccwq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hudajhfn.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2futdzmet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gt2bwbqtmcg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2dqvqpzxe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2iyvjqdsy.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2barndycw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2qjacnxyr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2bblyqdtw.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gt2nwafaprq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2nhurbdla.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gt2rjxkmldw.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gt2ibxbxbbz.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gt2gjvpeuri.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2zbhcqgiv.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyzcqkri.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwmjrxnh.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2fcckwlok.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2igfogqzd.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2ancbaout.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gt2wzsijfve.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2bwgqsssj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zrwfrtsk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2rpmqusqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2rolawqvj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2zvszaqnw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gt2nrvqrhvk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2qqmgyaht.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2ihcryxtl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2myttghla.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2ogkhqvdj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gt2oqgqwekg.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2krxbcfir.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2xwjslnrs.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2iuqwmwui.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2uiybuuya.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2wzbenneb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gt2chbsatzq.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2jzkumoec.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2lzlqdtqb.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2foyyqjae.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2zgqixsxg.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2hyualcum.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbapsdqt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2nvaddcpn.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2tmshbeah.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2eqxfvlnz.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2hvgvwfzz.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2qbqotvrd.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gt2yjxovqdh.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2otrswvoo.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2yuxbxppx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2ozqvmkie.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2qzauwmcv.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2jsnqhriv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2nsnsmqvz.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdqjciip.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2xgucfglr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gt2whnhlpjm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2pqaonsst.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2hfjeislq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2nszxqlua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2kdiavfbu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2viijxjxc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2qupdszot.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gt2xkrxqakg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gt2zksgejew.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2lmfzyapc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gt2chcqoijf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2tmitzfrd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkwjjuz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2xhqlajmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2blijxbkl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trrtwaly.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2hjxddixb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2enubhylq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2rpsxtfma.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vlurxatp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gt2fsplzlew.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2papnmdcm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2cybhoqeh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2tstnclpu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2etomwjog.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2ikjsvmrc.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ktdxiuha.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwpwwfmk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2ndxaggnr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2ysniodoj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2krxvecai.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gt2wuujeghe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gt2ewespkko.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gt2ueialbck.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2dvefcegw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2pzounsnc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2opqpavuh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2wljrapso.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edyprfef.html


<!-- 参考信息 -->