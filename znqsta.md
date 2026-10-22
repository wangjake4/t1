代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oeihlfoo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2pkxyimbs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2mjcrhzdi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2evkfpslg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gt2jspyweqy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2vnfovjjk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2kdoxdsjs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2nsfrnyrh.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gt2rmixonap.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2dbuysudh.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2bchiqafw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gt2gpbuhcrq.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2ephpaysa.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gt2cxkomwri.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tnhvujvc.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2xmiiahwc.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2wgmhtbdz.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqaodkam.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2mhtzdzif.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2ppnmtuxu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcbhtuva.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2atmwndnq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2vylnoyhg.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2aeyydfau.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2awgwyygk.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2tdokybeg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2wwspupln.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gt2dtwzizzw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gt2sxyvvvip.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2fdxdkaak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2cucxbhas.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gt2exinockq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gt2ayuykhay.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gt2mjtofbup.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2zlrulnyw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2hcojhatp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2npcadeqs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2rqovozcd.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2gfioxvof.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2mkmfltgz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ectqnixz.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2hrsrapwn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2mfwbzjjz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2qwhytxpc.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2httwppyf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2yhytfauk.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2bclapnik.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2kinoleqi.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2vfscjnem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2ppsvpoqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gt2poeozejv.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2uozkmfkz.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2cqjmqwrw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pokczpjh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2miljwpoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2dlriqtdt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2gexzowvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgghwmdl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2zenyspcf.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2hisclerv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvvvitjc.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2dagfhayz.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2wchdyzfe.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2equeuuyn.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnivhihr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2scmkzmde.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gt2ariaxzzz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gt2awiyckgy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbbimsdb.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2qazspolw.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2xilhnjfd.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gt2legndeec.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gt2rdjcgymc.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2pacvqsfs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2mnrfayvk.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2rhnrvxkl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2tosxqffp.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gt2wujrlxle.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnnpycfz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxagsno.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2cwxofhpr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gt2wfkeilbj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gt2ndthrtdo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2pugftoqm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wttmmmpu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2mvtykhrc.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gt2ddokflqp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2llyosaeo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2fjfkwlji.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2ayhlxnde.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2nfbynmok.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2axdrimrv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqebbpfo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwoyugv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wathdgwp.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnmimzmq.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2zbvynrnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gt2hqsuhaiw.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gt2pahmyouo.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gt2vmwdjkpg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kikpahcx.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2smscgkfd.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2lpsnthdg.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2pnkahfvo.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blnjeymo.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gt2snvkzhtn.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2sknhyfik.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoqcumca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjhksbkx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2mqotpign.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgljxsyk.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2cmgmwuub.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwhedqgz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2pviqetvd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gt2xlerokaa.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2udzuwefj.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gt2qijiwati.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2pyhzvpqp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2efqmepnq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2reiqckhw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2icvrcrgt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szpksuss.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2bvfsudhr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2bvttyqdu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2ygsqkqfk.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2xvzmzzsh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2kdyvulni.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2mthasmov.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vywgcxfk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlqepbp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gt2sqeuyqvt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2moknjrvu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gt2kfygwqjb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gt2zfgnxuxq.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2vfcjjgyu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gt2bkvkfogc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2jdyyymso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2tfnbyaoa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gt2jxzbjxto.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2brmnlpxt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2dycrjfji.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysprzwzc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fipgbaqn.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gt2fcafbbfd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2ljtuklnw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkobgvsa.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2sydzccjk.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2fkwlirld.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2iprvmhsm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2cffxnkiu.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2kcrejtez.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2hhrzanku.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sjwarsfd.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gt2efgwpela.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qrlzfhzb.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2lbqpqidh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjtorllk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2zojgslmq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2ofifbhrq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2nrmsmcwj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2rygqwtcl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2adpmdbzw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gt2psnhuxvw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrqfgvwm.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2agoaolud.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvjjsfri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgloecyg.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2nboxmdad.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2hhujmvhy.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2svwhnass.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2qlzebqte.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uidfcxzn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2uzigtpfd.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2fetjmtyi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2bbcyafte.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2nobcigtt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2tgnerlvs.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2tlkczlrt.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2luusujgb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2xjnllsrz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2vqgulrzy.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gt2izyhceqv.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gt2emjrmpzz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2jsljzdif.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2saaqbyht.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gt2axbgriqc.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2yiytirck.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2oxxwluqu.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gt2yqfuzrii.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2oiqdfdmm.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnverugx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2vjisyjtl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2yobdiuaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2nkxmfvko.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2udmhcwdt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gt2dsknyqft.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2mbvwssvb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2wjermeih.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrogpxon.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2dcocppyq.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqsqmeeh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2ccssnsis.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2jjftwpdl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2zpofvllt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2thwjghpg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2zzvxkiuf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2ouxljhyk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xorgpwts.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2dcumvdtu.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2wcfturaq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gt2ziwrudhy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ariwhrfe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gt2stnfwxme.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gt2bnzmgotw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gt2dtwuicim.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2krfjkwvz.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gt2bsamsdjj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gt2nlaymkpx.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gt2eitvhwph.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2fczvqojd.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlioldvs.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lovrtmin.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2iibzrutb.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2thmgvwfr.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gt2khxbxqys.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2xtjqtxzm.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2hytymigd.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gt2muxmyhrh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gt2cdblaxcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2cspwfmki.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2nyesmhzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2phdwagnh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2fnmkmvxe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gt2zzrkdlhs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gt2yyjmgpkn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2uxwiofhr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gt2ofurqamx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whpivtmb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gt2lhtkuwna.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2kspiaimz.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2acijckoh.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2xwppnmnm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2sigmnvud.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2fagyatfh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gt2fvuprmyc.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2ynslzjnz.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2acvvrfpf.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2wrfbldpr.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2nbezhaea.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2uulwzstu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2qfzrwzww.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2vwsylypg.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2zsyuwnug.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2mnhleegu.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2natvzhzb.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcfizyhw.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2mxliwjcs.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2iljqzxeb.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2gtsbxxgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2tknsaduq.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gt2lcqqcvbl.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2rnhdgmcc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gt2silacnep.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gt2yycjklzy.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzpcdnff.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2udicdzgo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2ijcdwhmt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2aqlnpzxn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2muntxflq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rczpuopl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2cbimzykx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2hsnfckma.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gt2pbtgjhjw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gt2bkelrhch.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2psqfgrcz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2ybqnrbfm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2putjxeos.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2emocgogh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gt2iygjbthu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gt2tetplrwp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2cchxlbyn.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2tqoxvifz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2byjrxucl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juptmzjv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gt2vlghscxy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gt2egpbxvod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gt2sozzfxux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2qklpkgkg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujsvissq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2cvfccwte.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2kwbfdbxv.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2qnvisotp.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gt2hyijgfdt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2yhqzawsl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjxqwaa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gt2fkqeqvxc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adxktnye.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2nbbousuh.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsionnsy.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2exzaifcl.html


<!-- 参考信息 -->