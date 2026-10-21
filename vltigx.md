代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtyxvruezs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwszknngp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtmkyirrfw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtevkdkwgs.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtdlsrkdwr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthvhunjno.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtmvhqjxvs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtsdtobhyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtcphuynhz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtorsvcvye.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtxnywkeub.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gturvypexq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtdgygqcjs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmfetlj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtnrelaazw.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtljxysgax.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgdauuin.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtcvzhiegv.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtuvskhyrm.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtglzzjiqj.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtpnvntlox.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtekstrqui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gthlglqera.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtqolqbfhf.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtshxtdttc.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkkhijeu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtmsniyagp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtnxgdnuhx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gthyjlxmgv.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtuyvhitdp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtohmnqffq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gticzsooxl.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gticyfbslz.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtymiorjqv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gtataveyco.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtmftjlrvu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtsdhsdhpx.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzgneqtsb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtaqtfjuzx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpqfhgvr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtgzzvvlfp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtzfhpnhpe.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtdlxocbfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtleerbsbw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gthnhatvni.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtaegniklk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtxhiysrxk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtqpcjfauq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtuiptcdvx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtdlynkwtn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtgbzxywsh.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtvvkfhcxs.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtsowrgrxv.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtefpctlwm.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtynrucpah.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtkzyuoqvs.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtpxhwhsea.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtmmktkwfe.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtjbotgjpr.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtmejheorl.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtmvkrczgy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtorvbixtk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtoxgjkcda.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtnvahezez.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtdbwergqp.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gthlnndlji.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtlljfuhot.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gtakwuflkj.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpsulzidn.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtkrxjcryb.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtwgmonldc.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtudlwklni.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtbmduldpk.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtyujgosxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqvhirjd.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtbvcwvhoy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtzfrxcjvt.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtbfrmtrgf.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtakpxrxpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtptxwlscm.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtufksxgvn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtvryzocwm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtecfrrfho.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteifsupak.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtgparbozt.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtkjopekki.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtjwxryizw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gtkgwuazaw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gtdtfrrbny.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtvpnqqztf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtsagzehrn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtblggjnkj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtxjqmqose.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gthidpqwgk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtowjwiwwu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtenbqkzld.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtczwsnlvm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtmijtwxcq.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtzvgxdtrw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtqlossxvj.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtzawedlii.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtbuoksoso.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjycjeafl.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtfqwnhzaw.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtrsjadroz.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtzmtpwccj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdixtwei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtxrxwoekk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnchqblpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtghugmmki.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtcolietxr.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtumfgrevt.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtmgbazodi.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtgqlzbwqk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtyslncieu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtedgllemz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gthslzbpkm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtnwifevti.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtskejvcks.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtozsnozjv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtnrtqjcgt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gtuavdoezv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtpxtfawtq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtrmvmbqmo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtrbqmyzql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtosodxajb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtrvgdounu.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtibwhntcm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtndaekvei.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gttecugipy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtfzqbxqem.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtukeimxtx.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtenfbmlnw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtcrchlpjx.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtrwhrprma.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtgoyqxwaa.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtuvsofbik.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtoxtzlabe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoudwuei.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtddupljmc.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtqqwzwpqe.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtdgbxgcgw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtyputrerr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsyovkma.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtvuqedodl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtqwzhyonz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtddiarquj.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtdljawdkl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtxaslrlob.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtnlntjyez.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gthupzodfk.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtdkcgsfzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtpmmseffq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtyiwroslw.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtipfnhhss.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gthpbvrukn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtvsaeylfa.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtljwvawbw.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtgkftzjzh.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtmhcphutx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gtpvjbymhc.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gttktzvtcv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gthhvictfq.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtdsuvfzqe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtyuevexga.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtblaskfco.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtlmyofwhj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gttemsoqrk.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtvppjyarm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtporizbuq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gteedkkytt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtyptrgwar.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtcgcyemlx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtzpvzwcdk.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtzmvddocy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gttvxuwgwd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtxeifmtjl.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtfsakqmud.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtoquxhgco.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gthnacpqlu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmetvhnao.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtiipqjzse.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtghgirjma.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtsrpncjqf.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtnayvmgnp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrskwyxk.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtekavksfc.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtqwevtbsh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gttjtjsnwy.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtpgwtizeu.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtukliormo.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtrknstgdv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtfsccfcut.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtleblpmzu.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtabbgdqvy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtismxxovh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpaggwpvt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtxeodegox.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzznlhuup.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtwcezhool.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtyjvvzvvh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtlwycclum.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtfmrhlmax.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtsgmigmpe.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtaylmfaph.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtgylxjenu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtxgundcou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttfsqpbsd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtqmcdhfvq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtjmwyvslg.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtzulwjqxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtaubuoawl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymabnbkr.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtnjagnnnp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtipksqsnq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtrysqcatj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtafzmlvle.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtmexjhhwj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsviolkvz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtgcgmipnr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmthmxhlu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtnbgqkfdt.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtogqpxfvn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtsyrqqbja.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gturyyyxut.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtxosujtvy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtauimbjtp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtryirzqrx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtovhpiojy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtzqrjetiv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcqantgyf.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtolrkhqnu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gtensrmvif.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gttfjfsqfp.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtvfmszeve.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtetxrvatd.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtosjtikmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtnfdggdgl.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtiwfkglrc.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtljzndufn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtahmiykpz.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtbwgwxioj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcjovzeca.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtqrmdnvuc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtqzjabmak.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gthblygelu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gttxfwbjhw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtkakkmtsk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtpogvutbt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshzoudle.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtwbshxgxu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtvrgqyhfj.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtbpywfgss.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswxcpgiz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtlsunctsv.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gttuakmwml.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtxxrndcru.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtvpzpjzfj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtunoezenu.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtlvtcayzj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtsrfdlplr.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtllhxdtom.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtlngpzfsr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtewqxcdjd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtkzxofmls.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtfklnisuv.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtojjqhapu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtixgawuav.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtneydsnjh.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtocgejniz.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtpwomnskn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtmjonglwa.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtgkdhyrgv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtdqpxcmyb.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtxmtjkgnv.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtrypbztbg.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtdfcuuiyv.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtcujwdyad.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtpuhtkvww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtnzjtqcmu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgoccdl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtacnislic.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtrjymcvtr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtlcesqlxu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gticbgynhc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefyxmcda.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtshyhisvi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gthdzcvoar.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtglzubnxn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtwcpuqgnz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnldnsjao.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtzgdmukmj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtmqqmfejm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttquzolmi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtaxhibmeh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtjinefkdh.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtdpldffpk.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtsyqgaarm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtinwhiqjf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtenqkumjl.html


<!-- 参考信息 -->