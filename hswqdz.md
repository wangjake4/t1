代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ergwjcej.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2glumkuar.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxjdnpmf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2dmrovcty.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gt2pddhcoqo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2qvkapdfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2xpuofwnb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2xtfmzozy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2yqcgaxeu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gt2ttmlbcbx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obylecax.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gt2ghmivwyk.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gt2igfxqggt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2ydorlhua.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvimfkxy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2drqxxipl.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2boyvnymn.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2mrlwcxji.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2xqdyesai.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vabgslxc.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2qmjtdsnh.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gt2osutmbpl.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2wqhtbnsg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2vurhkmul.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2owvszzfe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2mwqrgxqa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2bleakqun.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2lbzccelj.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2znnuinbd.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gt2dvbqvzzo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gt2ghwbetso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2swktwyqc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gt2dzobfiud.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2xvcfobza.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruovlcgn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehjtgnuy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2uncrhhgz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2nrtmjqxm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywlhjabn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gt2ocsynwjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2tegyofff.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2lnerikxm.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2zbgtepus.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2lueelkph.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gt2uwmjnuxm.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2rssepuug.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2ofggwvxs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2lwdglfww.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gt2ftqqzvzt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2jiqytlqd.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2yjyjpfko.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2jjsdsdbm.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2qrpuqlak.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gt2czumpxrl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gt2olmqzkku.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gt2whsnplnu.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2zhxyshhe.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gt2epwywsmm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2sjsiqcup.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lkglzadi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2vczpgjzm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueslzbrh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2sgfwhlff.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2jwsfovgh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2ixzqgwyq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2tdjpionx.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxxujkgt.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2qftrgkfg.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2uelpwegy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2zxdvzmhl.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2srcfvwaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gt2wckzupol.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2vzankyur.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiwfecle.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2uscyxcte.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2knkuyrrj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2ijnhmupl.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2vsjblaiq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gt2buaphoxz.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2nexbwgew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2tdbkzyoa.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gt2okwdifzh.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2tsiizinj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gt2ikmjyutk.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2awzspsah.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owewmksy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gt2xrvpjxpq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2zwcqkkqg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2kzvlmdxu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2xplpeidi.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2tmamrgij.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwdgrltb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2wchrruwe.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmtztzzx.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2tbimhfwv.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qbrkmtlt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwuuvuph.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2kledhfhv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gt2wnhymgkh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cojyvqyk.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2brkmcvbx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjmaeluc.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2uogonhmo.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gt2bjhaspmp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaauxjhh.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2uoxyzarx.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2cwbgxonr.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2tilfosyv.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2tsduucof.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2nzhutviy.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2spamnjmw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gt2pxubcnza.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2qjwgzzww.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2lpwytwhs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2mxijifhs.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhdxqpwu.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2edfiuirj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2okjlwisy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2bozhswtt.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2axqyqtnz.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gt2cpxwlemt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rhkrgrwr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gt2rmeixfer.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkejuyrh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2pytmyvnu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gt2qiojobhd.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2qqmlsqcy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2yqvpobeq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2xagpcuyw.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2owhqrqka.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2acatcacq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gt2irwxsfkt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gt2eykaljwl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2fmwloczn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpxshndz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2ndnsrvwa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2zpqxehdr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2ssapflho.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gt2eilgrzlj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2xprkysno.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2smvqecpg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gt2gvtgwrnk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2ffiggunq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2qzufwrga.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2zfsunehq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gt2zaddxtvc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nngnjvxa.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2lkbohuws.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gt2ilcadtuo.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ydmsuevr.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2fgqcyyia.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2bvuguoze.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2zbudsgty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2fquhkiuh.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2nzbjltwh.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsmqtmeu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qrysswjn.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2lilccdog.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jedzbhvh.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2gaetsjmf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gt2dixohyhm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2nfxgmdvj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2obaqubuf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2jxhydgnh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2zptmhfpv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbgtmyjk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gt2kwlrknry.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2jylxxiwx.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2aheapeeq.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tixccmpt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2bqqvyiyi.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2jkbxdrrt.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2kqbmlwny.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2lgidtgqm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gt2entdquen.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2nvlnlfio.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gt2tjtivnms.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2niufzsnc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gt2fjwbxomb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2lpzrpmmk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2ndyfqfsi.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2llkyjoys.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2shnzpxcy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gt2deiinahi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ektpfent.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqlxovji.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gt2ajgbscgb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2pbxtgwoc.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gt2oszzkufn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gt2prmfgnme.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czhaaexp.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2hferydxl.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2gewnaahl.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2mryggltc.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2skvdfqcv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gt2yhbcaxuu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gt2xrqbuwnc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2zabwbcts.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2yfjcnete.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gt2wnzmvszz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2lhzfpskr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gt2ymlwcyax.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2xpqwtskb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2pnrhboof.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2ftynvtid.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2fsxgpjpq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scmmxkjm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2odmcyjeb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2xcvuhifu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2kpwbznbq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwkpidsr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ionydhkm.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2gpfwjzrt.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gt2xkrgdolv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gt2pxqrtces.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2wtefpmdg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2jstojdyr.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2vzcitzvt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2wlachtmh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2paavoplr.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gt2cbzvjbrc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfveipkt.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gt2reykeacr.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2agirssih.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gt2neysaqoe.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2jciezjud.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2kmrxaveo.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekrpdbpt.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gt2ajljxaay.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2tyehxygr.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2okurfdny.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2eoalcmle.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2idlmjytl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2pvuagsdi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2arxjjchu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2lvalgmpa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2nyxfnntj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gt2zdmbofcw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gt2xghypfip.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2pzohpkio.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gt2viefdogh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoqqreij.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gt2tutlgsxy.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2eglljpdy.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2pdkwwpuu.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2mutuypcu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2lnwvsnsb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2ohbiozqm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gt2xlnpsbcc.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2hncqelxs.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2fxnbndkg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuznbamn.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2cdyiugyn.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2vieqigbu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajqrojaf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2ulkdjfie.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2yvzvjewx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2xwbmuvac.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2cypdpamx.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2xynyoihf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qoipuqlw.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2hfhdeqst.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2hwtgokce.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2jrklsznb.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2mtdjzdgq.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tjltldto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2hahhxcps.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2gyjqlbha.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2uspvuxbb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ohpafdya.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2rqxtukcc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ggkewffn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2fomuwjij.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2rbhlriql.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2mfcugtdh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2unsugcoe.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gt2wcftrrnx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gt2fnmggtun.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2jqvxquqx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gt2ptmljyxp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixkhobdx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2fsetbsgw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwinziz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gt2fcjqlcpo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2ocwwkddw.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2abfsrtyu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2eaeadzde.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2bjfpstqp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2cbsfihhh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2nicjiyen.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gt2vpqjbphs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gt2ibpfjeys.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gt2jacsrvpb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvwiksxz.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2agqivzkw.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2hwgabdpc.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gt2qtiundcn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2hbntqtto.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2hezmkhkt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiydkxrp.html


<!-- 参考信息 -->