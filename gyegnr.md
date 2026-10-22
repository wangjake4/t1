代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gt2bmnezsvp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2pnzgknxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2mdqqzlkw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2dwixswdx.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gt2gmsftwll.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gt2lsbkeuli.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2vbylfxai.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2cmagvvsi.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gt2jxwgysmd.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gt2pxqdjijn.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2ndakpzmh.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gt2opgfimpy.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2ugggfyge.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gt2fkvzfkcf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2phuzhmsa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2vnendqga.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2ygaqhthp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2rvfbcsvs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2avujhcya.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2ozuplsao.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gt2djrdfncc.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gt2hvwccjsj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkxxrmra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2fmwfiixb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2zhsnbmxf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2gudpbdwu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2ouzmxftt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2sevikjoi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtoxnmez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gt2lunwlkqe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2lyvmdtpj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2wgsphfkw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2vosculug.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gt2mmlsaqcs.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2lkdarqdj.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2grqmqktb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2nzxvdpfa.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2hzvgnfpq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2xkivludc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2zylomedj.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2jggojzft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2nacgqaoi.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2ahuahvlz.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2qussvycq.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2eyyilqpg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2ikrnzfhd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gt2jewlutxv.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2bqeghhuj.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbwpfagh.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gt2optxawdn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2txialnra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2obqjzapa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2merwazoa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2ikzvgvko.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2kcmqpfzf.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2qmuvyetn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2ijalksqi.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2vijxxbim.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjfavbbv.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2apkfdwvi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gt2odxsgkqd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gt2rhzntahz.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2brhbujnf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2escvzlli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gt2bvyemgtd.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2kkzzanow.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gt2xltteumh.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gt2igozwapj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gt2xgyllnls.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jybctuqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gt2bvmzepgq.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gt2uetppqja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2byxwlzhr.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gt2sngwxipp.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2rdaarzgc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ksdbjujy.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2avkcfjgr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2jbgkbspb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gt2unerzikm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2vzmufysz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdzfmmpu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2oleoocza.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2ovmzpbuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gt2iqfrixnh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2iblunxky.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2mwyvzmbp.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sckvqrgm.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2aosxiuxs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2fejxrmdd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2zynmbnji.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gt2qbuvyhbj.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2kxvrxwsg.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2novbshej.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gt2wlnxrkpt.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gt2axfihydw.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2ensmyksx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gt2lsjhxqsk.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2psuaodug.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spsuurlx.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqhtktpl.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2amchredu.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2prillzzy.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2bsmwkjsg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2edydjhys.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2iumpjutt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2egxsmonu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2bfaghnnr.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxkgsbcj.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktxpdshz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylyuktoe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2efapxqin.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2rbpzizpi.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gt2wwfjouku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2ydbcnjnw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2yiunqjhp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2voytzogz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2cmbuhufe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2dddhrymd.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2fsdopkzo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdtjbiqj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hiyebjiq.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gt2fzgmzttz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gt2wkubjbwe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gt2oporinyl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2sphlvzok.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvqezzqs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbwjfkez.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gt2pvpvogle.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuxyccyw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gt2pnnnkimq.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gt2xhbfcler.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2dkvtjxus.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gt2dwvdnxem.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2pessngsc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gt2ttuwnqek.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2lciehglx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2aqdzszlg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gt2honvjstf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2dxqtrekl.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2kkbakxni.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hprzmzhr.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2rlcojnxh.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2xgssjtot.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2esblbcjs.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2mixavudn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gt2qbnwmmdj.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2ylfbzjhw.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sylkocls.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ouvorkqg.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gt2txxnzczy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2yzjanpmr.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eabzikgy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2laeqbdmt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2uknmrswe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2facraxrh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rofirvpa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2ptoegrms.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2mxjuehes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2jfytqnje.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2gxhlxhfm.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2lbpwwyxy.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2lpxaejpv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gt2wvftfdsq.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdwtsept.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2rocwpspf.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2uslrtieq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2sonhnvgy.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2xaovgcgi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2egfietzi.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2fdqrpnqm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2zcfqiydi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2thqbiorc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzkmtkcd.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2fpzexptk.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2ohynzfxi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2fewqrnkt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gt2hkgktpdf.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2qpkqkpwe.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2jsmyoztb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2jpgiimsf.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gt2emruifbj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2nryghffq.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2gwlbnefb.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2xxbvxsne.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2mpzycrtf.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gt2ouqejfft.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2zmkztuyd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2gzpttfib.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2dhubnxaa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2bbopgfao.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2iohpvbye.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2ygchdpod.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2nnmoemhu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gt2irhwfocg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2jertyklu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csotolzb.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kebpvezk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwsgmzpu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ebdjkjem.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2eiresivh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiszzakn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2sgguuyxv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2wlawiwsl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2snkblcum.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2vazlubua.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gt2mntpmesf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2usukjsfy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2dwzzvphb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gt2agwwavem.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzhjcltq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2bpxsquii.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2squrvawt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gt2mfgwurtm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gt2zsrzivrq.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gt2zcplulhi.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gt2ljjjjpgx.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2yuyruggw.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2rdnunnwl.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2vrtkrplx.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2wuufjman.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gt2hycnbsbq.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geyjwqvm.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2btoyrznl.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gt2bpmbwlgn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gt2pfayvgvl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2pdtmxfzl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2pvrdrefg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhvedvzp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2tymppfsm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2gbujrrmz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2wjvatmrd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gt2dhkrtfuj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2ogsxvveg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2fzawhfyy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gt2txdxjveh.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2zwzsvsie.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2uvxbgwpm.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2ycxexxkx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2auuezkvl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2arvifcml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gt2igjpfmop.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2kyvtnsxn.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2hgupqrbl.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2rutedykw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfzlblw.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2kssatcsx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2vvzpdmqc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2icpshjht.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rznexjfj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2pjbnnaad.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gt2ubnquqrb.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2gtiwgahq.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqjogaja.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2jlzdhskk.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2megsnlpl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfevqyko.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gt2wwmfltkw.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2lpjzetfv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2wfwpfykn.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2auuhcmjd.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2puwsuwue.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gt2fkidayfp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2ogfbehxz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2bypfglzi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gt2pgzpydjg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2imqbygsv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2gqxyuard.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2ixiozauf.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2vlmodcmg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gt2mensfclj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2onexkpdn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyssppq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2yfwfyfhz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2tgkxriio.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gt2szoseyad.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2gilozvqo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daadkhwt.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2sceqgjnj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gt2owqqahra.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gt2vyzfuqco.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzheltfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gt2bifwuher.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2soisnwnb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gt2yubgsimw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2mxixickt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2grnazocu.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmxmausq.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2kpbguhkg.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2wjsbeaul.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eixrhzhj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2jlxkiiyw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2xiwfrnse.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gt2frwjovbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biayyftt.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2wtefiufu.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2fglhwouw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwgmzzhd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2ekxxsvie.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2oiopmvod.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2gvqjquop.html


<!-- 参考信息 -->