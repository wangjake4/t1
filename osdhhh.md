代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2pvpehjkc.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gt2edhlivtl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gt2smrsgnbv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gt2dpapfhuy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2tsdveesl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hheuuxzf.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2ndfwlumi.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2kovnubsg.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2pvayumgw.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gt2wrtxcxsk.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2zckwwxur.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2atqwmokf.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2ywfdvkew.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2gcnyvksi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2dqoivhgf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ubpknchs.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gt2cjjhfaix.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2hfrpozdb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gt2nzeqyptl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ztwwirvc.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gt2grrxkcsu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yrqjuavl.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2lfxamgem.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gt2eyiakyce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gt2nntoqyci.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2zhpkmhyh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qenzyasv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvjmbfok.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gt2zkfgaslg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2vvhifzhi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnzaonol.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gt2tzautaqn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gt2rmwwyyqx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gt2bwrszenu.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2dniirmpn.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2bjotoskc.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2weeefdhj.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2eyltzfzx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2hvrgtots.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aksfosti.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gt2ubpsdmji.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2wldnsraf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gt2lcnoqzrj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gt2wmxtxszm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2uhhzyqqo.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2cshatiud.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2evqofmea.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gt2wpujgtkp.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2kxtsgaog.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gt2jdxcpvbw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhfqjspx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2uzbyizaj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gt2qelyqhtg.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2vzbfaukb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2pbhxgzdr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gt2fhdphhwp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdnimccc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gt2afsstpfe.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxlfyshp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2jcbfjnfy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2pgxucyyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2mgltygep.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2syzxcmrx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rimmzvzr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2kexcdgox.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2vasrmiqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2aqkqiytr.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2bpgxudpk.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2rhbpwkzg.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2lfohgzhy.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2ljwsxuez.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2xveomqgf.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gt2iwsycnkd.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2tjegqdca.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gt2vrwtszec.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gt2lryqkrdx.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmwsjncb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2fvirxypa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2mkijgyho.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2ecdrncpj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2gcuaskkv.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2gselonfj.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gt2emaasmyk.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2fisaeiwk.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbhegdxe.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gt2scmdzcjp.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gt2ucywhsvs.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gt2weflxmki.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2snfrpyjm.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gt2ivxykuaa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2ljdsarou.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gt2zizlmzqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2wvjjtyvj.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2thrqkdyw.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2eqzwlucm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2wtolgxtx.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ilggsvie.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2xsbzvkpp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gt2inuknrxx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gt2ujbeenam.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bupeyryc.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2zvwcurpv.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gt2znqjzdnk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gt2nhjodokv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gt2brhjaliv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gt2xroxntbq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2aywselaz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2ikowcgux.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2bnadhpxa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2eiysoqdn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkjuxute.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2iwfciiht.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2uepqaciv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gt2xqgoavxu.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubhqphmv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2gvapoewr.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2muxexdzt.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2ejhbmoyt.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ortpayew.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2criqleqh.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2ulsakxgo.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2egjvadvk.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gt2uzlaarsv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2lfchnzpf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2vuuoitwy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2epbpbchu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbdesdbo.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2nxjtzttd.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjhvmayu.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2xceymnjc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvkbuxdt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2welbhwxx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gt2lcotlngf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqljckeb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xijwtdmy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gt2vtedlyip.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2obggzdmo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gt2slqzkpih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2hdtbglfe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2myjhpzse.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2fvbxjbbb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2sxlteyih.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ufzbmcdv.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfzzisml.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2flscvvrx.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2ejukutbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ozmbndfb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2lbkmvitj.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcqjnwhm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2ahydthbi.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fghwukcf.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2ljbmhcwr.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2kuztqzsl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gt2mwwejhzf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gt2xpscnmoc.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2ukzqsekl.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ejzlucyf.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gt2qvlrxffq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2anoyteru.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2amrcupwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2lzhtqzxo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2iqwnvqit.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gt2tbpwpqrw.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2toqfrnwz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2osppddeg.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egbyqmtg.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2wvvkktak.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2jfznhxcx.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjjfjlji.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2gbmpgasq.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyvxqskv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gt2jhhklpen.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2iszsgxoz.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2eqhwuwix.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gt2wiflauzw.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2oyhpzwns.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gt2kohdzilv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxqkueht.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gt2gzrutcpf.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acoihgnn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2sslxtgop.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxpqoxks.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2xvgcgukb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2bujkegrl.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gt2artzsnen.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cctpszks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2hphmppvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2hcuyiqnf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2oxahhtmq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2qlwhxjpf.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2xpcmrynk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gt2ytrdxayc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2wohlsoki.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gt2phsqcecj.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ljawijdx.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezlthujm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2ayfaxnlj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2vmlrweym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtyjwxqr.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2tcdgxslv.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gt2omaplohx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gt2gwyyygub.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2vtqiempn.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqctkhss.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2dxnwqaxu.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ydwsclqu.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2hupaqkpi.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2cssyeflo.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2yrxgjfyt.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2somngdtp.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2renpjylx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2taqbvujz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quqfoeqp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gt2zifzuwjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gt2ufaiqgnf.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2mgzuqrwr.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2heaxflnf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2gqwmjshd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2jptcyjss.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvzkiafd.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nomafhoj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2wsxexfge.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2khysduya.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2wvzpazhh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2zskgkxzq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmlgejto.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2bwhhqoch.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gt2korgzoiv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2ajfmxmgi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2bwltlgfd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gt2nhnudhdd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2hphwbzcq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2gwhzldop.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2vyehxrvr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2pkzofgsn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gt2kavgqbvt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2lszkvcby.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gt2vkrphezz.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gt2gvoxgkga.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2tlxmauhx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2nqehkdxr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2olflfidk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2bhltmcuw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2hunrkrbq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2brzvuvqq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbsghurz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ibxsvajk.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2vtqbdmac.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2ekdkymeg.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2dmxumczs.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2srbtezek.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2xckxftxi.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxiqypho.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uljkslxg.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2guhumqvj.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gt2arpxjmvm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tobrlzfl.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2jvjctkax.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2obshmklg.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2eqfqipim.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gt2yuntulja.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2hktdmoqc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2ctajtyzy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ucghlgzt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gt2sucnsxjk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2wmtilvxe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gt2zyifkkog.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tefhcgjo.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gt2xhafaxep.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2qmqdmgaj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gt2zopyieyh.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2fmtuujsd.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2skqsmjit.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2atkzsfkp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2qzzbkkpq.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2kfdqxzca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2vvjcvpao.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhxdumw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2bcelrusp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2uzdajokj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2pmtyjaka.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2bxfgdskr.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dznffxza.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucarautr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2gbwhulsc.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziwimygl.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gt2sowdaned.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2nhouoocf.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2yaghdxfu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2lihhvnwy.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2mgbnhwfj.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2fsclgzfs.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2bxbobaty.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2pfwfjstj.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uagkjvex.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2jpvxvozw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gt2zsyabudj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gt2irloxqtw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2ewmmxuvw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gt2dmsbetpy.html


<!-- 参考信息 -->