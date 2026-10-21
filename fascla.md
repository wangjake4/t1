代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtwhdyvhnd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gturmwuejp.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtyglxysox.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gtavuspuuf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtsldzpozz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtdogkxqzk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtpckynnob.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtwvzcxiic.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtcgesfxgo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihnglpyw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtktjjlevz.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtsjwjsgcx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtvtwerner.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtnlmxjbyg.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtmnlmkzur.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtiwlebpej.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdunujlf.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtkozniplv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtbmqgvlto.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtmwnwtnrz.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gttxzpllsq.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gthauemwjx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtvfifzhsa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtkaqnxbrh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtuokdogzd.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtgbwiambr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtprwephom.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtyzmgptio.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtnpnincha.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtmhfyyjvh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpdxyajj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtdglvxsgm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtruetfjwo.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtvtkhuqlk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtakkhylor.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtmzcismvx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gtojopqdag.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtjolcftfs.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtizufwcyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtzkjrdmaa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtobopempt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtekccuzgi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gtzkjurevi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtdwsoaqcc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtwbtqbuvz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtgnuusitn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtdpzltqws.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtrkmmnyto.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjrsymadi.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtoizcrakh.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtkkznkxkt.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtvgiskyxp.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtpepklweb.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtazarpchb.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtkusntzmw.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtlapxkmgj.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtdoyrvihe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtkexfwbmc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtdbpejjzs.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtbnsecqer.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtgwvfnazl.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtsxpfyvur.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtwlvnbqae.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtpltpqkfm.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtvhdaibxw.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtkzkmollz.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxxsnjsy.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtbtbdyrkj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtqzzygjip.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtrucfbugh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtibiiqkns.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtycakrofd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtpqqhqksm.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtahalgsqd.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtnnyzqcjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtsveidvjw.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtuvnafngm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtnwixbmxp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtkdbditaw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gttdjosubd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtynjfxwws.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtpfxvfiqa.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtlapferzs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtpntipaiy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtnipvcayx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtnnltbrvt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtenqjpfis.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtriluehbz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtjhwqwimx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmprtrfla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtsuugvqio.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtbjuluunl.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtgfzsklgh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gthduxxxdh.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtiqmwtfpb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtdbxprtxz.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtkstuoown.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtvkrivfzl.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmnlyapbz.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gtkvnqtpez.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtwatmxnoi.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtklorbgak.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtfbdrvnqt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtgrgyoumu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gthpnukobs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtdlyipkjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtslbelpzh.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gttlrcpjzc.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlxcwhzuy.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gtwqjxxcrh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtelwgyned.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtqltzipjc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtmparqpcf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbmwgsjs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gttbcrglvq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gtdoyuldjq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtnwphejxk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtpsqiwiac.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtbiwlirij.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtcmxbpfif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtrbyfvmti.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdjewkior.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtgnaaejbb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtnvaezzuq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtombjkyfn.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtivuwyjsa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtafkbbycg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtdmwuxyrp.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtezdwtckx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtslniwxrs.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpnmvyaoy.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtggjojwbz.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtioqmmtin.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtagixclzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtlwburlot.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtsrtjveqx.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtofcgmckz.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtdvigisfi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtnkgtztpl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtklctupnq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtdpsagjfi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtwrogylxo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtnmeqsbiy.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtmzggcget.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtcpglmbrv.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlntvhzwm.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtmkajvtcw.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtompajvgv.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtbsrttbor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtpkeuzbik.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtgnpvymhm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtqssmjsrk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gthvmkgwcg.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtlzxmrodv.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsmdpjmz.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtybbdlqxk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtymwevvuo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtzmonfrrl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtutyrmkxl.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtmhjnymkg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtbyozncew.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtuewkwpdf.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtkqtxbmli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtemobngyu.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtjmlvigwa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtvkxjrmuy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtopyinriq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtyazjxena.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtpeununar.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtzubkhtyf.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtsrypxhlq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtjndszofb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnkylzdq.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtppqtpeac.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtrgbyhcdd.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtylnpgyqt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtykysdmyb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtrlvzzfkw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtpriihlzj.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtzfotsnzg.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtyzxnkzjs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtnoipwfua.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtjfcviccw.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtemopljpk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtyjnjawqn.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtivtojwuj.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpuiwfym.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtvzheiddj.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtfuggjyar.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtmfuqinfa.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtvzcpjylb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtiwsimvrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykpsjjsl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtfimodygi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtcbmgtzpd.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtpqidrffa.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gthlhpjjgx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtpxgbeyca.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gteesjvuhh.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gtbzhaismr.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtkrllwvug.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtryzlwwmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtnzmjtsqq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtgtjodfhz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtvooikclz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtwxngmvgl.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtlreibilf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtxddmypeq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajrggdh.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtpialjrao.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtmigiwwln.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtfarvhtpx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gttayeghmw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwigckng.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtpudxptji.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtlqprzmpp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtbarsutag.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaajzqfm.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gthnpqzkig.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtwolhvdcv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtybymcekd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtjfgguquu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtzwgiiwao.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtrvpeyfsw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtesvctxft.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtugkggglo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtimvvkffy.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtmxmfmqzt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtrxdxchuj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtepywedwu.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtpgqpswpa.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtgyuvpftq.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtgayzztcu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtwktofczy.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtipglgtab.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtoysgsnuu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcsjlsyge.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtzbxsmapt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwoetmzag.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtszlgqhzn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gtvvajkrbj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtytkutlrl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtjwhlgkop.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtkjfxlohh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtrtdkywkc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtazbpmbet.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtchrxhklo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtzwgrdawx.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtzhfxbbqw.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtotfahtsg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtftadyxrp.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtqcauonrz.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtycofpdzj.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtkwbxcetp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtwzhlhuwk.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtefutdvjl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gthevqhuyf.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoqzpxqh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtlleypxwh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtgfgtswhf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtlwkvhdlp.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtruczujyn.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofijrmyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtaqifaunm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaasjwyj.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnldvfbj.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtlyqqghsr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtoypsixco.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtwbvqyqic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtwoqfemer.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gteljhlqpi.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtnzqqhzfo.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtsoldpcrd.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gteevcyimt.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtvmlizfps.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gtuurdepty.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtgdivfpmr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtbegztqtw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtiohojmxv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtshziumbf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtncnsdhhl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtnbqcknre.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtbfwnegdb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtaebdaycp.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtrcqisvkj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtxdiqfkgr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmibrhdg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtdmkxhqxi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtqpaadjlw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtntrtwrvn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtqcjnihys.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtvvktcuwq.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtyoxcqapt.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtnujopcmn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtfngxoqit.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtqtvfdqsv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtotzcschg.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtgdxvwdtt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtbiqjfior.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtxutbhzci.html


<!-- 参考信息 -->