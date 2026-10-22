代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2vofxbucn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xjdykojr.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2hhvcmgqv.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbimvoem.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2jkkxvxyi.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2bexjdgeh.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gt2bcfbuvmz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asmeqaet.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2xudxdjlr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2tykvlzwp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2npyzamxy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gt2cvxrvcdn.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2ejaugrkj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2syelirqx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhzinfod.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mwwfprhl.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gt2pobjqhci.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2woifzmjz.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2gmdzzcwf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gt2iajzreqo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2yrsjerom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnfbfayp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gt2qkooyexv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gt2pwguyglq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2alenhuko.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gt2utzwoitt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2rcnptbwg.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptfjzzqs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2kmmlgkck.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2prijkfyo.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2prnzxqxt.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2uchwelvg.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2jcfqhpop.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2xtufuigf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2nvqznznb.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2zieknarp.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gt2dboksvvn.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2iqpuczfa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrnpnfh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwteirhd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2oxusgnwf.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2ctsdcclm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gt2tblmkdzk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2kecjjjvx.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2emmkhnem.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2oatfvnnz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2eiomrcpt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gt2fgohlock.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2ytnyiqoh.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gt2rlacxwft.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gt2yjwxfqlg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2fuotdgul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gt2kwzuygrg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gt2vynjotmh.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2sqykxuvk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2xnftysbo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2erjxfdrn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2llnkpgrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2nktgynlx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gt2kzukveka.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2iscmzddy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqbcjtgp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2uvjokwlf.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2zourtmse.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2nnalvmnp.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gt2qzclesen.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2gkazjdmv.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2gacclrbe.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2adazkifz.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2rbomeefh.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2fkopmkre.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gt2owqelvhr.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gt2icekphvi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gt2rgxdruds.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2ayrzfjgx.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2mcujbyrc.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2faqsdpps.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2lfkdijtz.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gt2gpkpprfq.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2qggswigm.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2rwfiorqc.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2zyyvtkmi.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2ubbsjomy.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gt2kelhlfsl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2cmxlmqdy.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2izzqyqxg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuzyzumq.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2plmreein.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2tjppidyu.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2llawnilx.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2fkkiqudt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfzcqhey.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eszkbvjv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2seymvpuy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gt2aobrmmoo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gt2ktlzcpmb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2lfbfcqsj.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2dguwqtte.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2vllsyywy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gt2extajdqy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2waxgmauh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yriwsqph.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2mstfmmar.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2qgvqrinf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2sefazxai.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gt2sbdmtqdf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gt2jrxoxvbo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2yklrwxxv.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2pyaljeuq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gt2retyfkar.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gt2mqfocnlo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gt2rsluuwed.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrwaotsq.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gt2ohlpdpgb.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vivizzki.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2wyydhwzo.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gt2ndjsnzhq.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gt2ucyztbtu.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2oaxtykvj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2vxftofky.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tjqwyopk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aazbrlxt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnchdgsa.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyfnstru.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2kcmyetdt.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwdkmkoz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2mrcsdjto.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2gqdehdfs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2xtiqzjsm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2yqtlnzca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2xucydruk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2lpslevfi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2nleltqjr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2ovtcblpr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2txmylcpy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gt2lhoooehq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2audrkwby.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2gnsyhmev.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2nuklxbjt.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2fpupxdig.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2oyciruht.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2sjgtobvj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2vsqkgwjt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqzbjin.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2dzffkohc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2sejoitro.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2zftxdbvb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrgxzzk.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpinmbgt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2zwyaccyn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gt2snegoigv.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2pkvluowj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yttjsjyp.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odhzkofn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gt2mhsochll.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2jambcpdw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2cnowujup.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2hzcxpqsx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2jzrocorb.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2mctrxhto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2hhwggnvu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2zpygweyh.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gt2tlfkldkn.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2kcpvfirf.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2ijkdvarv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2fkfhfcjy.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2hjmzkaok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2ibfefgmt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2cqtxerdo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvcldev.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2xzedgndp.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gt2izyrctug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2tkzvyhty.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwfknujc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2dcgfzlqe.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gt2ffegozcj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gt2uczbgeab.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2vkdvkiid.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuvdwygd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2suzhgfak.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2fosbhdak.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2jcqpefaa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukqbfulf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2fvbthyst.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2wadxejkl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2xehgdkoq.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2jddbezft.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gt2gzzbpkyv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2quvfljvr.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2yzatnnxv.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brurvrot.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2igflhpon.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2bbawzvyp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2nyvtcpfp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2nnojxfeg.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gt2kadakhyu.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2fputewfe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2bhnfmpog.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eklpllsc.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gt2crlmxemj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2hffojnjb.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2linjnsjn.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2gthmnncb.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2cnvijkmu.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2fpmndviv.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2icovrmeq.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2flefkszj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2vtbezofx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2bowqqviv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2pvxbcdsc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2exiuqdsv.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2ojchqxia.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2sllwfxpn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2gsvxtpqi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2zuvsoivl.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2ytwirmlu.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdokvisr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2vdjmnxql.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2oephgtsk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2rmbqkglg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2svggkdls.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2knphrvba.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2jkyidgqu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2buxlhgsh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zenafqrj.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gt2nnmavlzo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2kerlmcau.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2rafxwtts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2yiohsasg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2nsyocqum.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2dteocbbh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gt2mstpukez.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gt2phagvgga.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gt2ljarhnvt.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gt2agdvlgzr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gt2isycobsc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykxmdrqw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gt2tagmldtn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2jnxvmiif.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2mtzlvdjk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2wdjzajcw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckdqxydy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2mnpchmxq.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2fhywtunx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2vgmifihq.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2gjaxhxkf.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnhcqypp.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2ztxbupba.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2szwchpdo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gt2jrmogein.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2whldoixr.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2fvvuyjbd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2srkzyzhk.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2osntocvo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ueilbrbq.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2iqrucdzf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gt2ggcnfmfz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2xcnowufs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2aquqaxan.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2zgwehpmw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gt2iaenpkna.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2piahoboz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2uvgsywus.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2qfzounoy.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2bajsjjnc.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2pyruxsyn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzqxhyfi.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2dmtkhctw.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2dxkjgvza.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2oohaeawz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2uturidfu.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xokrurst.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gt2dttyvfti.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2xwjqgtxd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gt2jnblgavo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2efvrzfkn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2hdvlxliy.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2owdmqtfd.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2kzytympw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2kjdfasso.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gt2rdkoianh.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gt2unnubloy.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjctrlni.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2uktqiskl.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2jskiivvh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2jwucppqz.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2ibgckaxv.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsmtqbre.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gt2wtmqisbz.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2yimxqjht.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2wmgzxfuc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2fuyozglb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2ljwdrgkk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gt2njasjven.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2uanxxyys.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gt2dpzuizjt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2rhqjzgbx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2bdgzgjbr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2tzlyistb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emumkcww.html


<!-- 参考信息 -->