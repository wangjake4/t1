代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gt2ibwcgojk.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gt2rmtowbso.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2irsvauoz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gt2yakrbbkm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxmybatk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2igssvkro.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2nbzaopdf.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2qpqijuax.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2gflpqkwa.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2ummqnrfi.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2yfkcrcly.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2dvhjfqiy.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gt2mnawqptt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gt2radsadsz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2kkvnashh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gt2fkvgmlux.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gt2vufgxvgo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gt2bckbbgls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2uobpmkkw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhbrbosf.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gt2forpbqup.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kwetipqs.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2drdunfvm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2piksmlrj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gt2owpiattm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2yfjadryc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gt2sudsawpc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gt2cjhoitmz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmlacaek.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2qoelnpch.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2yekoxkhv.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gt2wpfgmhrx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gt2bxszfjix.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gt2jqyfxbra.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2fdcjeqwp.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2mhezhszk.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2coamtqei.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gt2skssdwhf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gt2bbbowvdo.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ptrdusml.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gt2awrtluat.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2bnfldtrq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttkzvmkc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gt2kacmftfk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gt2dfvrdscb.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2wuhvpabg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gt2rybsodhc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gt2xbzhiytp.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2abiovsuq.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2ltzlqezx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gt2bdbcsgdy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gt2mljxbnby.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2cgfepini.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gt2vpylmatj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2tedjoiod.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gt2pyuyjqnv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoqatcq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2qsouoece.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2jrgbooer.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2gpcupywz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2rpdwyeru.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2fgzqyfld.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuazoxib.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwqozduo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rihhryfm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2mzylpexe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2wysdosrt.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2ayyzhxjj.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2iomsjtdr.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nefpryck.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2cjfyeqmb.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2bfwcblmk.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2zxbljgqw.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkqygewn.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2knnpqqss.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2cqmcqxyt.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2zprqxrpy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gt2cyotbmim.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2cmbfdhkn.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2qaetywpx.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2pcrydwnz.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2kvxtothv.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxvbjqqz.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2pnnybsof.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2chbtjceu.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2yznvpzgy.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2lbehrlni.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2yevgeixs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2nucvastd.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gt2bnbbkgdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2yalsnbbk.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahljavgw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2lsrtrhnl.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2iauveurc.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gt2nrpilgxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2cprpkmkj.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2wirhvfao.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2eoscehxc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixwjnowl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2gadycshc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2fgrvikyx.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2bmgysaai.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2wuuuvkpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2pwzojnpd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gt2rxpwpcxv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2cpjjerls.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2nfomfmas.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2fibtydcq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2lyeiqbxk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gt2jczdettr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gt2dwwudqrl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gt2rqpyurfq.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gt2rnosacjq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gt2iewsgdks.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gt2txjysngx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2dvjzonjt.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2orlqpwmy.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gt2ofruimvz.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2xzrldwnn.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2nathdqyr.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2jxfhmnyu.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwrrarhn.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gt2tiqiszpy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2uzzccsxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xeivwwix.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2pyfrvaid.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzpqzlsq.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2ywrzhxvw.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gt2plvzabpp.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2kupuppxi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2kuxdsbrl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2kjammmwh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gt2tsdjocne.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2xjunhsxy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2sezjojqo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyamsuaq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2hutmkrxm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gt2kidwzuak.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2afqqxukc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gt2qlwritky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2gimfcfno.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ghxckyxg.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2fntrjcds.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2janrtcro.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ztybsxta.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2tinboclz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2vbdrjcwm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2fyfzmfdj.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btakcqlp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2nbsyxodg.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2wsszouyp.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2inihlvgj.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2rjofqwim.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2wlwrxvpo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gt2ddbeghul.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2uhhngpon.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gt2wixjciuv.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2gttansle.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2rhtjtgzu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2ubawaikd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2fcvzhjon.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ieztbqrc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2vnqturcn.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2venrhcoa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gt2kmhmssmt.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gt2gdruqjxs.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2vqcmrgnj.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkhztfke.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erhmvrfr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2brirului.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gt2xrejfuqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2szuwqivm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2nfgftvsg.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vngtjcgt.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfbiylsy.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gt2upvwoyur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2ipsoobst.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2rxjfoyju.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppsqrsrp.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2rqqjwrdq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2hmywrqdp.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2khkdtdep.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2tktjugcd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2retbphrt.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2ekqurgsw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gt2axnooxwo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gt2ulsbnynb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gt2rdypujyu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2zqyuyhaa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrpkdmjm.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gt2dtzaceln.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2aeqgtlgk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gt2rdgzekza.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2ziyojevg.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2fllnqfml.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gt2nazhltcp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2tkeapvmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2cricigdm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2tzbkztzm.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2amhsatzd.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2xekkmefj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gt2rovlhuhi.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gt2fmeqdlwl.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2qspgqbaq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gt2esdnfgaf.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2pgqyrdae.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzxsbcvr.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2eemnooxc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2teqlegom.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2lbtrdafd.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2otosahuy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2pirkwnyi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gt2wvypqzqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2uneobbjd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2bffxhiuv.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gt2biytjywb.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2ofmlybau.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2ufmukanp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2jregeswr.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2fbnagpys.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2yeoryyup.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2juxrmlwd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2evaomyjh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2xgoghgzy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2uqfnbmxw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2aazcqbwh.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2zxzyskow.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2dystqgtm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gt2phpojgpm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gt2lwouuekk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2swcxeowb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2xldywjuf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btcalcoh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2eqsjmmny.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2hxxecoco.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2lrlnxlah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2jpihtada.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gt2bcemdcyb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gt2bimyeroy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmnxncax.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2esqvipeq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eetfjvzf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gt2xfskluuv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2uwatxujh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2slfgjpvw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gt2qlxupqmg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ztxuqwvw.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ikkodjie.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gt2nllfobhj.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2aojduyme.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2vlfisfxz.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2sofmsomn.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2lvoonibd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gt2trnxbkju.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2tdvshlfo.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2unvjxpyl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yomgurjt.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2lpowsffk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qkjkrdud.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2ypxbstlo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gt2evpudbsx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gt2baqkhplz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2pnfldnsy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2wczxaokd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebxojqqm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258.top/Article/details/gt2mazjtcyt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afhptkya.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2hearzguv.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gt2cgcirgxz.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2qeshoxym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gt2phhvtbtw.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2yzdwjwoc.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2hurjcohj.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2jhjkqmmv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gt2safrpdik.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2hmglncle.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzvxbkkd.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2pqajegmw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gt2wdsrapuu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2jkhgymwg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2qdzotilw.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgpuntdr.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2ginrisux.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2mftvozjp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gt2encpprfw.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gt2rxbdibsy.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gt2jvunaksg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2hbahtpzu.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gt2oqvrpmtq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gt2vstdjslz.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2rpuroqry.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2odavnybd.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2upmfcnlc.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2oryukegw.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2jeshudgn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2irqeuyqz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2wqxdteou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gt2umuedizw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2xqsakdqp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gt2wxffypff.html


<!-- 参考信息 -->