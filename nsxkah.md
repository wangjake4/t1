代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2kwwhhzhz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gt2miupmmvx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gt2rpnwtmmg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xklvspmz.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bshdqung.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2yxvvabsh.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2emsxcjxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcmrkcbs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2ikamhxze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2enfarolf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2tvwvhpxe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2zrbpnxap.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2pgbwqbau.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2fapnnivw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gt2hmgrvqqa.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbauosuo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2dldexygx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gt2tdvdovka.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2usgyiyqf.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2rxwkacvb.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gt2hizgqcfv.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2fbnlgief.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gt2ydawcrpd.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gt2juuzyeez.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gt2utyruqpr.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2olaeiqjy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gt2mdyaubhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpfpvmro.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2yvptnpnb.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2oczkroik.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2aokgwokj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gt2ppcgajeq.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2hfdhfncj.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gt2wddpxwom.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2wuaxqjcf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2gwyygodo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gt2wziuigbz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2tdnkixee.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gt2pvbytwym.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gt2jsyrvdat.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gt2pghydfmy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2mmwytngy.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gt2wdxsqpql.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2kjxfgkxd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shoxzrtn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2zzcegvfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gt2krjqfyqo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2jfqntheo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2aofufjwj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2kauzhkkx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxxayawu.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2mukpncyy.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2qljqahyn.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2vwivigpz.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2mpydevfh.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2bnnzphdv.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2igwqcusz.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjnquapv.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2uqdqprpi.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2cmultxuu.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gt2xfgsbgbs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2uckmrmrt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2thxcanxv.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2uzczrqks.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2ullmnmkx.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2mraajlwj.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gt2ysdbklkv.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2wadotctj.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2uyjyuppb.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2rifsrzii.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gt2pkxrlumn.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gt2dzmgpofw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2ttmxtcok.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2jajjimvc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2nvzckfnw.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgjjcsmq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gt2kqdupukq.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2sszwrhza.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2xrvleffx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2zlitxjda.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdyymlhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gt2pdxexhfe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2uehtzqit.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gt2mncyjsdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2dhalrshk.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2tdvlpewu.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcysbftv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gt2kifgaqra.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlrxrrcn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2zaoyxduj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2crkpizmp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnzbgotg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2ieodipdn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gt2guoqkire.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gt2ztqjkxel.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbpcyzg.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2qpdyboyq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2ltcbdqho.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2qxggmlug.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2wmgjroqn.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2rlgrpynj.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2cgjxgpxi.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2tmlglhmd.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2vyeoojrz.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psuvpndb.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gt2exlwirnf.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2skmywegd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpdiwruz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2zpnvpnuv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2zqonhgyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gt2cldbygyv.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2uhbtbvkv.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2ckimrdwa.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2ossnyyut.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gt2gfxavady.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2hsbotycs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gt2tsueqprk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2agspbatw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggxwfiaw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ddavefco.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2ezamsido.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gt2ljmwyavv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2xiyoclsj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnclgmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gt2lhuwzuuf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzfdphcd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2ndueqvdt.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2azmggmke.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gt2ceqtwqfv.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2subsbgvb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2ytsuuvqi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2njswcntu.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gt2lnkmfstj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2odiqbrly.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2rdwkawcm.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2jandeuyo.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2erdafinl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ochulnva.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2tjgfrszd.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gt2yfcwzxzo.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uscozpat.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gt2asorrgag.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2xuhmampj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2uwgflwwt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2friylwvf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2pzezxkbf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2rkwzudza.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntxwoeuz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2eptqqohp.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qymlkkhp.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2vkedfgtc.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2irkbcpsy.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2jahtabzv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2syupsjwv.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2kgchqenx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2ecoiucbv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2yqxjzdok.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpyzcbeb.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gt2izrdblqg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfxsqoi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2gemspdmv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2dlauunlh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdproftb.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2nijhgaiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gt2loghgesu.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2kzvdbsfl.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2aopkzjkd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2cbreaoqj.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gt2grxkzmnl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2owtikrqw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2sasshzbi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2iqytesiu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2cnirkypb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gt2vgnipaso.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gt2hcvjgolh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2icqqozru.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2ftsadzkv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2lljacjpm.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2kqtkkqvk.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2bsecgtpl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2xwvnaiif.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2uyxpgmzy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gt2pyiawfth.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gt2tkiwkguy.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2qxgyjbor.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gt2momppbij.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gt2ejtnyhce.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aktnxsnz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npahlynb.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwnsximg.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2jlaepfpt.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2dxjyfqpl.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2xcndmuqk.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2mhnplppc.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nrvxnecm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2tfabxlyq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2tudayxcw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gt2ugzkahvk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2mogvbqcg.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2mguzsndq.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gt2rxpipneq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2xfjregzr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2eppvddfj.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gt2pqmdhtqz.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2yrrhustm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2xunfzria.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thgpwyia.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2wsneephc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvtbccxt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2cybieioc.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2unbshgwb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2ojszgphd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gt2ysviafbv.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gt2kqbvcmbu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2vuczkmkx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmqclozm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2qrfliras.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2oozodagv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqapwme.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2afgcxpfq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gt2lytakkrn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2sqwjklsb.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2nwfuzpkn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2nuhalymy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gt2ubrgqjul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2tfkyevfk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gt2jlhcxasm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2vrgrjsym.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivlmsisd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gt2tfetrduw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2donpwpup.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2wfnttanb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2frqbulds.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ovivsbvh.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2imtuuccl.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2rdhtqxzw.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btllwfao.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2kulvjvof.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2yenlrgfc.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2iavwinwy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kstspvgf.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gt2bbrtmhdc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ibuubldm.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2mntutezm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2xtxnvwbj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2btproima.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2khzkeecb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2uwxwrsix.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gt2xtplybbt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gt2pxrjbgxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gt2mqnlhumc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2iyoixeyj.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2ikpkneex.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2ctfwtzsq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuogkgpx.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2tttzgowf.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgcurxse.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2dzpxtghp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2yzsugojo.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2enqtmdyo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2fygegjyy.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ojoiivro.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2ycpumxzs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnijasry.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2ezsmvfdy.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmlrkjbe.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2tezspdje.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gt2nlbwwzjk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gt2rkufquco.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2pbppzjjx.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gt2redutqwa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2seezqpyq.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2ajxnbtzk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2anggqpor.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpucgsqf.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2bcuawmxn.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gt2eouvqfkj.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2brbassye.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2zemvsohu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2lerxxuax.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2xepupbms.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2xsfvznak.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2phwuercw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unskmcoh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2tknfrxwu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giiaqayq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtefxraf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2iocsywap.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gt2jlohgrxo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2lioexfof.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzldsjri.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2uaklgvhh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2hbnuhpvd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2txgzfsmh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2danyflnp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2wwvbrksh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owvwbjvr.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2xjxtwykd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2dzaqdraw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2mwqgmrkj.html


<!-- 参考信息 -->