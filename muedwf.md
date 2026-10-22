代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2ovnfchtr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nmsdftpt.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2xwqivifb.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppqnzfot.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gt2ffdjsgnj.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2kvlaqfho.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2ihgmbpfy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omxvhxiu.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gt2lnqkztwl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2zsqstomv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gt2ezwwrneb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gt2oduiegps.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gt2buazjvgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2trrqryrm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2ubtjwonf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbjukxel.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2rlycnvyd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tatzcfwo.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2hmbocagj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2duzsebcw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2wlwfxkto.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftkapmdd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2isrxrzis.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2kbmonsod.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gt2imobepnw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2dpophyou.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gt2dqbupmmj.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gt2vqcyikog.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2kthanmpf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gt2kvsosamn.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2buuudslt.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2foahpcjz.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2okjiokdc.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2lgjtvovj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gt2ntsymjog.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2dzqrrmrm.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2nvfnjghu.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2xwqhvxgw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gt2fwfhjogg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2epsnkkps.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2mdbyufwy.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2xgikixel.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2gctxrjoo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2tbmcfhgi.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2mygkmnqq.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2wkqfjilz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gt2haziqawt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyswntzn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gt2tkodgbgh.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gt2qroimlqx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2pxblegna.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2zwnfhxip.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2qzirikzv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2lxrljzlr.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gt2nmkxxtps.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2dwxbzaga.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2xrcvontn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2kybsosjt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2qvareucn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2gdrgeifi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2jkzmhwlb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2edkxgfbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2nupcbpgw.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2pnhgdtoq.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2gexmxyqd.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2fzfdweey.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2hymnfkex.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2juiqynqs.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upuwxeel.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2noushlnw.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2klsnftuz.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbbsghts.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqccivbw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gt2wyawnuhm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2xeguonwt.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2faikphpg.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2jxbdavgx.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2setqvrxm.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2rpzkxajt.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2eqoxnpwf.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2kwmzgwhb.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gt2nkdetouj.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyvqbotl.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2ifnnxcvv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfxygcsp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlcyujk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzjghyrc.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2ogleuxqe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2ygqoadgd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdczyvpm.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2bzdjjcdr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2cqjioeht.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2ipdfbibh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2eqenqwxc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gt2xdjdafdo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gt2dprkbttf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ceeobyql.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2baleafds.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkewgudb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2knieshbc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2raanmsck.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2jyrklkuz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2cldbwmow.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2ndddwewc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gt2igjveaww.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2gewkoufv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2keqixfbi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gt2hcsrkwcn.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gt2brfxevex.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gt2jvkerjgv.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekssxfop.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2pxjinhsx.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2eqtiyomz.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2vtfcaffb.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2chyjgrmr.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2sflczghm.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brmacuuh.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gt2dbjrrzrr.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpflxcuy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2azupoqsm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2mgtzupbl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2jitqlrzo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2fuogbbul.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2nzptwvff.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2edlztdbw.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2fsbbmtjf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2ztzkruiy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2pjokpysd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpmmebma.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2hnspjwwn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2gimrjewl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2eihwllgo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gt2iabddjhm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gt2owpsueof.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbfdeiwn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2xdagyifu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2tmyrcakh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2flogwhlt.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2bkrdaulb.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2erhkiiln.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gt2nrlyyrtz.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gt2efwdmgrj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2ozghefwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gt2dxusikon.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gt2cycnnqqh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2rluftmcn.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ibhdyjax.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2uastsmjm.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2dgmufxwn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2bluafwpg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvoitiei.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2xnbbocis.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2udynnjmd.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2opexrfuh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2itxryrzo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tdaagbkw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2dvjsnwvc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2jabdgojb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzcaegap.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gt2mnkcfamt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2udcanvet.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfvvikxo.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2seglcowr.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2kulinzex.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2egbbsvpl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2gqojnwya.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2wetumwde.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2pbznhyvo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2zlfgyywg.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gndlgiuy.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2sltdbbjw.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gt2zxavchma.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2sixzouni.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2tgadjmux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gt2fkjobaln.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqonryr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2pbbazfjv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbubqjun.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2fqmbevwt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2vroobezm.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2vmwvrzsv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2hyokryoo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2aszntwdt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gt2kfvmpqah.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2wwiijnym.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzxzgstq.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2xizasdni.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gt2bxgcawqb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gt2wlmswctd.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2igrtqzku.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2rdtknzsh.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2nyotziuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2farnaiiw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2pqpwejmu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2ffnweuht.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxvfwbmd.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2xwnqmczs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gt2kvvyufky.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckgdlwdf.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2ijasqbvp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gt2hawesfpi.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfupdlqh.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2gjnxjque.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2igdkzcit.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2sbqgpwhb.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2aieelqcd.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2meafdeyr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gt2zvalpjxi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhcvhzpf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2dhxbquol.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2jrdsdihc.html

TS:   [...arr];
来源：http://dali.zycfv.cn/Article/details/gt2wtwgwngw.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gt2kdhcjspq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2uxhrrsgu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2hztijgcq.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gt2ewvbjwod.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2doiuggwu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2getxjkjn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2yxvnctgm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2bcjmtuhs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2xbmbcpll.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2hsxljyrw.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2rikklwdy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2rogyupzj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gt2vpjtvarm.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2akgdezbr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2bcpaxxbt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2xzeyqomy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2evaekydo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2ghzprmnq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gt2mcdcoiap.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2zckvsrni.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2ifrsvmqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2gujxnjud.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2jzczplyw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gt2gllpszcz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2rxfjhanp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2lgbqkjsl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2ycepwhlz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2jopvnjpf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2thsbamcv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gt2giglsful.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tswrfwxp.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2kekpfbfn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gt2yhpxtmhh.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2hkeinnqe.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvpdyrto.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2zenfxjni.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vblevjer.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2zuswkgea.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2owewdibe.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2tpjflvjm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2heinaxwt.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gt2vowwlkcr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2kokdzkgv.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2bvebbycg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2nkkfauvq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2sawzgtbw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2qlnqnyei.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2pyfxnhbi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gt2kisnefiv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2tzynhrsa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2qoeyqejq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2qnbookkl.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ncmunxyx.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2taawrgdk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gt2mctctdjm.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2vmbrygfk.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2bwglfddx.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2mknobcrd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2zzlbkoze.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2jdhijujx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2xqzliuft.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugsgrivm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gt2qllrmbak.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2dezmxuip.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2qvrdrnvn.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2iukdlziw.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2xlbouzsq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2ukujzvpu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2oumsjphg.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gt2vjhlogpb.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gt2pqlrudji.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2rhrnfvqp.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2ikwwpxqw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2pvqtvzsv.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2iphjrytg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgxmbae.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2dlbputff.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2kkbxsmri.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2peqkaolz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gt2gclttqfw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gt2zifwatce.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2mbdxkdjl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gryihjbe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2xuxcqwjc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2yockusxv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2siasopos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gt2ftjctsxr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2ugevgmdu.html


<!-- 参考信息 -->