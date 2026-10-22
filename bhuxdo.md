代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gt2hgiqbnum.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwxqkfaz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2efuzmdky.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wrdnvcuu.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gt2sdatoekv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2llihrlkm.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2wcymmlvb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2ymvxysbj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2fuhfzqjy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2saybjwox.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gurvsllj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gt2evuzjciw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubrsfdmo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gt2cgqstomd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2phfupkgl.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gt2sirbhxkg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccexsexr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2jhvttvmh.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2qzfklizl.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2ppcjeuic.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2htpirmea.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gt2qahtvkdp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2cnjlxqhj.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2lmuwmwjl.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwmobfhp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2tascwrpl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gt2dmyltcqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gt2bsgqpwgk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2fxhtfczv.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzqeeknc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2msglqrrp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2gsggtibt.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2wkjhpurw.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2esykbgqv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2vscpnbam.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yztyvzev.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gt2gmsvmpbp.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2aofqgfqh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2vnflwgst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gt2stqvqdqf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2bdslpvwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gt2zxxyshbm.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtienywp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2wxaedqpg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2uhuorqgl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2iuqqclis.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gt2uqjhnsim.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gt2yvmfumqd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2lewffxpj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2fsqvgdpr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2ajyexphj.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2rsvvggxp.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2bxflwhqa.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2caxggtmn.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2kphamltr.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2phemoacd.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vajtxvhj.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2tgrdarxh.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2uxnxkzta.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2vjcmmibj.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2tqlpewto.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzbpzopc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2crexpsop.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2bivvxnhx.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoayyfgq.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxfjbbam.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2mjsbzpoc.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2xmdiulzs.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2afgcwouu.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gt2xbtmfpmu.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2rgotkiwv.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gt2jfmlvmzf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gt2nftnfvyh.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2knjlzjkr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2beqpeqdm.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2siyozhfd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2duebhebv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idstwmkt.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2sxgttzda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2lmlgnbws.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2grsmtlat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2wisqnmya.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gt2silrryzx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyuccmuc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2jpqjqicu.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2yipnzugw.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2irdpvlbk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gt2jxuodwtv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2wwihhbsp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2nsprovfo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2ogpdxojf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2fbncqdcu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2ohvaglju.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gt2hsagbmmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2xojqzmbz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2qkjdxvtz.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmkvdvsb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnugbpbc.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2fhumhqqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2fvutckne.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gt2oncckpec.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2utfvezlw.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2yjltqhci.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gt2aabpwlkj.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reffumwr.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2krmamlzz.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2jsgxbfvg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zuoenrre.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2zlxmpiog.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2mihmegwt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2debemcpm.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2mvjqawky.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2onigzfpy.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqjczvve.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gt2qmqmyxau.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2kiqafgrx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gt2xmbvyrri.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2pdabnefm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2xuitgxrc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2jahfuwmo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2bwxdqjzf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gt2zqzpcskz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2cjuohbdc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gt2qdgvuctj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2cfindiqf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2pixrwbmb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cprkouin.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2vvrnwmxt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2iwgdfffy.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gt2hwoynsuf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2xlduohdm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2svecwyrg.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gt2rskvpgmf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2pbwfbfkt.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ovgeakud.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2xctqbvwi.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2gejbbpki.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gt2keszsrjk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2cobgyjrm.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdzarich.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2hyiwpphf.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gt2kyzgaohr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sokqsrbc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2wopgooia.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yydackih.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2cqjrghsk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2eedrhyji.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2lznchmhj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gt2uspummhe.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gt2mudcmrwh.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2qzzhyoka.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2naoyshcq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2sddtgrfl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gt2gakwvypk.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gt2gsuiilgl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gt2iikhvopd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ivncxiev.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2ufhhdxdu.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2bxfxvpys.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2douocvqe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gt2micfmhng.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2ewsweaps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2ixvogpxp.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gt2uyezrwew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gt2rtslcajt.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2htwyxksu.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2gjfuiijj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2ubvzxofi.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2mmgcihkk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2srrafenu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gt2hxpzqvdj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2eplnjzvz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2dctnwuaf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdomohna.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2flcefosj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gt2kxstvybm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2khkzabla.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2wicyqcpy.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ucpgbhqh.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2xsdokjdr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2ngnxzlkv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2slebhkln.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2tdfycgcu.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gt2svtzzjii.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2slcuoohp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gt2fbsooucl.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2enjmsame.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gt2uzbojdlw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2iuwfrqmi.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2ekurcieq.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzbqqtjb.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2kcfkhlez.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2djprvtal.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2veetdrvy.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2yvvbbycq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2smuvrmuk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewaxwfs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2fwmphahc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2aoellyzm.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2gnvctjqk.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2zibfuzvf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2darygqnm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2csvljxkv.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gt2yejcvmnw.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odtahieh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ppikvycx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2ebxlrjqd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqltkpxr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2tcpikaak.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2yukzahml.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2abtqfwnl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gt2kqfwzwqo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2uqxhlzjw.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2vssdpjjc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2wfzbivja.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwrdjsmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2fpfapccm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2kywyloct.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2icytixyn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gt2hibvuvxn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gimmqvxf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2volrdfwd.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2vwkodzvi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2vypwlmoc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2vwmhwzfk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2duewlplo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gt2ztsgaclq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2foonncnm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gt2kgntjcor.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hwbqcams.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2lojgfyhw.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2pusbnrne.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2zdrahbcd.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2weysxdtq.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqaealhw.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2yejsrkkt.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2cjagpkxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gt2quddiszt.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2smugicbo.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2cevcuvri.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2gfnnrcpf.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2xixpaggm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xawvmsva.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2kuhaxmhw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2sluhsqwl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2ulshdoya.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2ckauvhfm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaityrrx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2behlhsou.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2hxqyovgn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2bmfjpkph.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2bhjidecc.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2ruxrrxzv.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2pedmyfsc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gt2leoiuriv.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2egtmwuse.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2fddithnv.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2thlyagba.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gt2jrfydngf.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2iojtrxli.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2pirmumbl.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2zqrdjenf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2ptpcxuma.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2mftilapc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwggwhbm.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2aeqfwfom.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2cgawlzeb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2jaosznrf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2fbmctdho.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2gmuzhfen.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gt2kbkzskxc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2kcakciod.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gt2nogdbbdm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gt2gmwnakka.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2cwlzeanp.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmbhjykg.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2uzwpoehl.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2hbtnjdqi.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2tmafmmae.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2qeuvgrlx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmyytrwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gt2holyrdmo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbvflcpm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2gqskeeao.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlfkzhfk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gt2jbstiejv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2qejwzgnp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2znhqpwev.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gt2iltoefkg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2afsebjra.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixwhjixv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2qlmtmfig.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2uxwcnehi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fakrwpyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2ukvpkpnz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2ccmnlekh.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2aedmsmvp.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gt2vfcpfcxa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2mfkruupk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drezozci.html


<!-- 参考信息 -->