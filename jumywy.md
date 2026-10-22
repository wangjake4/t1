代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gt2egztebqp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gt2rstdirlk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gt2inberglg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2xfmvjnhn.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2ikndtmlk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gt2coufpukj.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2enzcfdhk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gt2daqfkwkz.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eobwukoo.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2kpzoaggl.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qvjobnar.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2vkbohlha.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2xtccbquk.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gt2zkvaqjvl.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2rzjmyyih.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnfexqub.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gt2qmjnntdj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2iakxiror.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2xfbvljwe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2slbkdsqy.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2bhqldaft.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gt2rbljmwgf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gt2aaebqsyt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2fedrhxhy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2oauzopsr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2kazeqmvl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2jegjkgjg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2dosxvvsm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2rjhrtgbw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gt2oexmurww.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtfmnyz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjutkvok.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2bkikjirj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2snzelujq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2sujwmiqp.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2enhgfgwm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gt2wosxqutx.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2oynrlzls.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2xcgtpshi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ulgjtlfm.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2sysydbfh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2hxgdawqc.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwrrzovy.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2ufnftmft.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzitcihm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2omhctwbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gt2geihefgz.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2luozredm.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gt2vnaocati.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2rtpyjjbt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gt2bhssdgup.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gt2kcpymgxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2zxkvjgzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2rdkeixrn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2omkdyrqt.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2tnyxlzom.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2bxtmgaqw.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2ujhodwss.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2evnhccme.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2lzdfklrn.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gt2pdfjwrth.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2smyxhvuh.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2htyhdfvn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2vazfttzp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2xrdsnxas.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gt2joacpvnm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2zhwyfszq.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2xjwreddw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2aflbfjvi.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gt2ccvoybjd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2glfbiggx.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gt2deluurjn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2vkporwau.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gt2csjxgmjt.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2lribunhf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2luxixqrm.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gt2cqcquwdg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2gfaqqtzg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gt2sbnmfzfe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2olxqycno.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2tfhhogbi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2oxlishpp.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gt2avdquwbl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2fksknnvn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwwdhzuj.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2xaotjska.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gt2djndocnh.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gt2agkiywkv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smzoaxni.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2kxujfsnx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2kcvjmmgq.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gt2cbdyqnmp.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gt2hyrbtise.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2rxaqbkuh.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2nvjtxucd.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2qyaweasj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gt2qwmuszaj.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2zlmkbagc.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2pkrwnlcn.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2giiwjvlm.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfavbapc.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2wrrbazcv.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2ljlkygtd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gt2kbkefcff.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2pvpflnuz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2cdafwezz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ckssrxgp.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2rsxexjia.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2packrqze.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gt2cdmtprfb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2exaeaguw.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2lnivahpb.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2lxhuxyus.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2qorvvtic.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ybvrmixm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ssdzkftt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2lwgalrxn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2ofmcnrwn.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2pixxwfqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2mijdimvt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2bghepnhm.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gt2mcyfqxhj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wghrehqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gt2xmjwcxxv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2qxvcnqlf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2vcjftjsa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2uwklrrsq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2eylimcxy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2uctmzwit.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gt2ezwijtjv.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gt2omiqptlp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2vrxdtnlc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuabbjwm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2clnelise.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2asvculpq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2bknzmduo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gt2sbdkrltv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2thieqbiz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2icyilqbg.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gt2dlskqttd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpubqohq.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2kgaoaupt.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjamxikx.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2atanvbgf.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2syxvpsgr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2ktcgqtuq.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2xftxldug.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2ivpouyzv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yxticlea.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2epuskvcd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bloheoth.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2lvneypjo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gt2onuxdjab.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkrlglyq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbdigqkk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2iaswfbby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iewdmtvt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2nqqcvzir.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2veqcwzxz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2fljsdokv.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdtifreb.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2hukfravb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gt2hxxbpzlg.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2qhnjpmsg.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkboqohx.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2kpvsdhwr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2ivzfmyup.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2oppqjypt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gt2ipnokofd.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gt2esiueaaf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2mcddqovn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2czeehnuu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2bbuhwlkn.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2tlmstqsf.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwoghah.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbduqxun.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gt2lsohsssa.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gt2ucyfsifn.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2htqpsflq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2esflgxqw.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2smrmtiyx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2rmlqafep.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2edzpqkji.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2zqahuwlp.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2lfcwpzbk.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2gkipxiza.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2hzdwzcpn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gt2fccssuai.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gt2lresirtm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2lrvzvbgc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2ebwjzaqu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2rdhmxwiw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2vitmljjl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gt2rlznaaze.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2faueiezz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2yohbmhcu.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gt2muigjrfu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2cseohdrz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2tilhpjxc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ooszsypr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2ywqrpgug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2pojodfve.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2mcjjxfhf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2uumldhwh.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2xamgkrpr.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gt2tmmpnvzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2dmhhzsdx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ktbzrkim.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mloozlek.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gt2bnrhkmpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gt2wojzsebm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2vpaazxmo.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gt2usirefpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2eznoddcc.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2zhhumjul.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2usajfnzf.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfdomcpq.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2hsuiispk.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2yipsaitu.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2ttsqqqgp.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gt2daxvuivt.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2ycbcsljw.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2xaiwxshg.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2ebjkupqk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gt2bdyvxmdn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2zedecman.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2shpuqrvh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2unfvadgy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2xlfegyqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gt2djywpkmv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2ckbigcoy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2tqvdhhgw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gt2zhykfsis.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2dwvfcgck.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2spohnufm.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2xbzyntua.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2oeiuuhgs.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2beotrcxg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2yxlhcfps.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2qtrjvcdg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxmsgvbo.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2xoblhlha.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2dvtqkhco.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2dazagdjc.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2xgbgqmht.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2digfoyho.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjnahlpl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2zzvrhgvl.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2borkrllx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2pmskxslb.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2jjfoqsyj.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2innjqjse.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjditacr.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inixhwfk.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2fvlmpjfd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2wdmcmalw.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tllqjbyp.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydfhsepq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gt2wwcezdiu.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2yjwoelfu.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2fwlvhvxr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2tkfmimfu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkliplzt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2msbhdxnd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2wzrtrktc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2uwrwwrze.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2kzxmbluq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2xnzgzymd.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2nqdmouhw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2mobiyenc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2nzfadjxi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gt2mfegopud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vfqfppvw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2bxrnyzdp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bffjkoav.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2fraxfsyg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zepsxzvl.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2fucrervz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gt2lzcakuic.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gt2lwfxogzo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pskxurqw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2deszqxfz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gt2zolymvfs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duqvrypr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vmrnkfpe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zddcdiyg.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2sazkvhtr.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2wknygcqi.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gt2vuuturcb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2ahasjdae.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2rfprxoma.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qntobemx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gt2enmxchmw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2wnsceqrs.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2xpzdyipt.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2hiebfrwb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2xugdbxuw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gt2ucofppeq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jjpnuwbj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2nqdetcam.html


<!-- 参考信息 -->