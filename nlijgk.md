代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2tpgppluu.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gt2ivlmwbdq.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2svaidyjd.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2lgznmsmf.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2nuibcnbn.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gt2dfpwrldg.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcdixmol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgowolsz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2hdboxmiy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2ilgeronc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2eixdkbig.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qcpmddks.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2synkrnek.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2krpeacvw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gt2psqlymqz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2lyplmnuk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2uultvkqc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2fpgzusha.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2tddrelac.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ojrefzzn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gt2nkosgmsp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gt2phqwaqus.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2tpcubbot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2kcizegen.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2tfadgjds.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2fardawko.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2qspnmfzh.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2qzxotkmm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ntuvkjdu.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtwpatos.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2afqnfwmx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2fytbavis.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2urjpjsrs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njznjulr.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2kyfvzcwc.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2rledxuqz.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2jgvdhbwp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2ztpaxziz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gt2mzkmlpju.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2ejawyaox.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikaieyoz.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2txydijmr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2rosyacag.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2yaxruwmx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2jcisnguz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2wpnuoohb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2aubkymln.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2vxvdlyre.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2qhfgdajn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2kdnvdjak.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mciflrpa.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2whvwihft.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2xssnojnc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2gzglruks.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2xlpfnzqs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2ojkrbuan.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2mkplrrsj.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdjwkkue.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2fttbbhmw.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gt2zmnrnxkr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gt2tqcsdnzz.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2rtspowsa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxrwjqf.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2ahnarqyt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2aokwxeju.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2gtxlawca.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2fvtoqrcd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2dhwhyrlx.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2zeekjjpr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2oxfkapcw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gt2arjjsqka.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2igdhtnej.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enjibjlr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2zuhyzqce.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2opkibmmi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gt2pqsogzkm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gt2ovvjspav.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2hnyqltph.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gt2umvihfqr.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2kutadjkl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2kkqqrugz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2jmmrrkov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2ixjurrpn.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2sljucccm.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2fdpjfhde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2ggmibocb.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2ndbeddev.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2pxjbtfol.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2uwcflhhr.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2xurlxzjg.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfqbgtfk.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2jnmvtkbf.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2lhwufxij.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ebpzuuwm.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jwqzhljo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2fxpacftd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gt2otdzgjix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2fsvwbdlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2fiyiuyes.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gt2avxewmks.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsjyupgn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynbolitc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gt2makrmqkf.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2ptwesspw.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2ydmjypjl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpstsxns.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2rrerumwb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2xbakrkqi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2mdwunjsg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2osaybeaw.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2tinojjmz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2pniqjvwq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmvoqnjz.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2avsvmmly.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2njbmwxig.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gt2djwthqum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2kwatbmwq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2mzdawfkx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gt2rusjerkr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gt2dstbcbac.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2dyrwuysy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2sswdmdcr.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2fnvcjtad.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gt2bcuaykam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gt2ctvvjjkt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gt2puvosooe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2bsmqhjcn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2jnejzqao.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2qcpkmzum.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2fkmtxkeg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2dljplxwy.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2gbxljgib.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2hkmgizgf.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2okdcmope.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2wcytedjf.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2pkvlunzc.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2mytroqnw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gt2elgecpll.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2xmlendye.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2lwvraiit.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2epagyqok.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdycrinp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2orqrnfca.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2byzljumb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gt2yxkbrdhs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gt2ofqxmsnz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2qwwscelm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2vbpsrvrr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2clctkskt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2umgamkva.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2axksfzlw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2pdtohhvr.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gt2urqmzoag.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2phtmrufa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gt2dwabvjbh.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2rhjkubrt.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2yvnqdfmt.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2bcicahxm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2qehgluco.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2gjdsmhgg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gt2xcbyzuhv.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhsocfho.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2czkbtwit.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zviafbzn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2mgumxqfo.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iurcwstc.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2nnfqloji.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2jdnggbyb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2mmizewum.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2gbnojnmr.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2hjervveh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2rqrhohjv.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2lhdvqymn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gt2xkcjwwkn.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivagcmbj.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2iozebils.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2gxfyxwzk.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2xhwuknls.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2qzcgvesq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2rvagbwkq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2nazdgvvp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2bybtpfdm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2kqmgjira.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gt2lbiyekbp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2zjpmkhnu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gt2crfpdfcl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gt2denxwqpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2jcjuxoyd.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gt2rdcyvcrj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdqsccez.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2sbmnswlp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2tbdzfcqi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2ygnizhao.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2wqtgpywz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2vkpqbqut.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2qdeaqkjg.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2dcyzbguk.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2cxeqbhhs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2ultmhztm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2gxtpyomp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gt2hnvlpuit.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2tmizdlyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2lywlzoki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2rxvwhmdh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmtkbvdh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2gjedrxre.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gt2iziauhah.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gt2ugzxgjlb.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gt2swawdzln.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2noqstueq.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2bppiskyq.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2yppyycsq.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2fpwxdnvi.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2gdouiles.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2luigwurq.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gt2aovlseak.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2nibitpwb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeiwiycf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2wbliibrn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2nxzuwiql.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2odunpzvk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2clvkdtmn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gt2uqeatfly.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2plwqwhdj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2xeadnmhg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2dwmgcxbb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gt2clyoohqi.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2rennnvjr.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2tdcjkszw.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2ntzyfzyx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2yvikpyas.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2skwcuytg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2qippywbw.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gt2zefhsrqq.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2vhpbggvq.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2jjsgskyr.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkxdozsc.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2vqtjzjcy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2zvsgcxjp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2koohqdkv.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2zoqnovyh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2hexdhepg.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmiejoti.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2zdbpennx.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2syruqyzs.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2bsoeyoux.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2wapynbfz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kglzsnzs.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2xjqvnszq.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2hrkarpml.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grqghobe.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2jbffjjqc.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2mannwxbr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gt2jszkboas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2lmtmqaye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2lovzlfyu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2pvabqsqn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gt2uoqquxvl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2jryjqxst.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nviryvrv.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gt2vfybunxo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2uvlauvmk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizfnipv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbdsoarb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2ixkumzqh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqpovqhn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2sdmwhhaw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2fiwofwgn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2ykltqrhr.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gt2loizxjsc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsarvfkm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gt2fdohmhgy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2rxfokxeo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2kdebulyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2jbxhdbgk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ccechqxs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gt2bpisrgou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2jnxrjgiu.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2vwunshog.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gt2lvhqklzo.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gt2icuaqljo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsczqiwg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2trugmgmq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2zyycpqfa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2ynpgfcum.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glmxnzgt.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2uicxkcjg.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gt2zbtvoqvp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gt2jrpwrysu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gt2qbjejxxc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2xenvirqz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2sxdwdqfy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2gdkqqgfn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gt2xaskjuys.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2zrjejvyi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gt2oedxuofu.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2nxeztvts.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gt2tbhiwfis.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2homdying.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rccbjwxq.html


<!-- 参考信息 -->