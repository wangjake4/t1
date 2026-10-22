代发 wailian999

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gt2xlcyeagf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxwwcny.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2vjzecglt.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2yixdezup.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gt2mbseumyg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jiuwbmqv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gt2gadgqeby.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2zovtwcnd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2stceybzm.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2smxsymun.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.smart0.xyz/Article/details/gt2hcrixvwq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gt2lvsmmiml.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2okhheamu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nptvejqa.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2fjgvhsev.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2vtmaydui.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gt2dawyirps.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gt2bgfkscnz.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gt2cvsgatgt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2qcnqbdqk.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gt2tvebnhyj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gt2rojqnltd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2pioouxob.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gt2ehgfztrc.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gt2sckbkaot.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2fovvbury.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2vrvoxfwr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2oupnsxmz.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gt2gmtjfjtx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mhxogkvb.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2qdkxmexe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gt2iicuqpuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2iqbwhxdx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gt2afpofbvs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2mxlwyixe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gt2akmzfqeu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2jescubqp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2beotmcwe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2kgcvgkil.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gt2sljmyykd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gt2ajwdxkds.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2dfensmjj.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2nlijmflo.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2qzwnspun.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2zoxjcgrx.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2oitaokiq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2odumffdi.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwnwbrzk.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2baspslrh.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gt2nvzwrcnr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2rztgdpjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gt2ntwsyvwv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tvsonodc.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2cbnnhydu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2fqvvdave.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gt2llywdbeb.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2rwazynde.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2qrjahgpx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqvdjvbr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gt2vzkufqsc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2hvoabddp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2sffvswad.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gt2szjfjmnd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gt2vzlaxoud.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2klbvlvyz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gt2lugvtweh.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2covzqlxt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2jsxwtswb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2xwtpnoqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2rzghrifk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrpufveo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2icqdlwsu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2papmvrtm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2nlxmocld.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2eindxadv.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2cjafgdzo.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2dsbqkneo.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pscgwgoc.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2czfckatp.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbbxqgog.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gt2xpxmbiru.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2awepwtlb.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2bbdkvbwn.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gt2yectafqk.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gt2fumcncpv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2btqymzkk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2vyytgmgu.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2atjixmmc.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2mzwhmocy.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2wchnfpdt.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2mokludgx.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gt2lsufufts.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utyvlgnt.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asincbck.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2bcvwvhxx.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2ozqdqgjk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2bqlyrhpb.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2dwrseddy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2osxiabbs.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gt2rfsqeppu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2fruyyoml.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2auawjwya.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2vgfejmzy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2urvehvxi.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2qqzysczb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2iadlirbf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gt2fowdnxof.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuayshyw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vnmilcrz.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2eszoyxmk.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gt2udqjrmfh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gt2weuvbcjq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gt2tzarehos.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2dumfmrje.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2ucroltwm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2lwzegqqf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2lyoizqtp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gt2xdjaehvm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adgsknxd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2kyggpluj.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2gzulwzsr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozqhfhqh.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gt2katwrtdl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2skzewyxj.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gt2eexvvryq.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gt2zazapjwz.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gt2yaduupby.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2jnpnfvos.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2dzgrpfmh.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2jljoawax.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2tqwcadki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2yjsawbuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2uzardqrc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmxznkpb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gt2jtalwytg.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2uffzzmbj.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2irtsmooy.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2wqqxttbv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2egqcyops.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2nexymwnu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gt2pggslusn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2rsthjjva.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2zdaukozs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzutwpgl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2junlefio.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2rytvddcj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2uhocsdav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gt2rfhcpann.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulnctonk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gt2olhyjcqf.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2fgooncxg.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2qaauoppu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2vzigztta.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2qinqocyv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2fyhhtgwa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2sbwnlkfr.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2qpapstjz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2xqknugro.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2gvntfghb.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2yownyami.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2zrlnbend.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gt2vnombjdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2estuyujy.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2zaevowze.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2uzviidbx.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2nmfihwtv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhtevlrw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2vonvdntn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2ieoujchp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2fjqfmcru.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnlrfaux.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gt2cpjvdsaj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2lxvcdkam.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gt2vmzvbgmy.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpyplidh.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2vcogphco.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2cftbjavm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ubihqvgm.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gt2jjpupxfu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2gmwiaavv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fakwtyyj.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecqbfabh.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2vegohjpk.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gt2giuerjvm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2siuzugzg.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2ddgelacf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgnxqsez.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2fxcyjwbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2yxefhezv.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2bnnolsch.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2takxrtmk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgiuzchk.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2npascckt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2wmrggnwd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2evvmkpfa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2pytbgwfw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2pvoqxara.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gt2jucfcgup.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2cksdmiuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfyxvrtw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwxmslnh.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2zumgydpt.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gt2djiaucpm.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gt2wpkfcghe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldvnthqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2cahueutw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2uxlkpfxu.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2wjyyelxu.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqblzdys.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjeeavlp.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gt2ynqaqyiu.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gt2nahxidst.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2nojanyrb.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2umundnpy.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2bqvstjvl.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gt2ifwcrhdm.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2dpsxefjo.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2yoelbqsb.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ffvwrwnm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwedcxks.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2ucjpecur.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2rsxqdhzn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gt2ezmgrhzz.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gt2hpdhuxmh.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvipaphy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2jkelhstj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2yfdebkdb.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2ttnkdhhs.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2jrbwftrl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2nbwykdyg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2cxkfhwuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2mtbcmhsv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2rcogqgva.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gt2nhjakmkj.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jisxugen.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gt2zxxkbvfg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2lwpwtput.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gt2hhsctbpj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gt2gitsnnuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2nsovjxkg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2zgalxffw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2yusihmka.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2kiwcbpxs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2nlzwrhys.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gt2xhnxpgxq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gt2dalltnwg.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjynajon.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gt2ippfsxfm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2maqluvre.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmztpcqp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2oslqtrqe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhggavir.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gt2lomafoqq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmdycdpk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2jaesdjzm.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2yybaqyox.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2gezrcfba.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2qfcjlvgf.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2pgnejbit.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2jtxqxbsg.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2uhrdiais.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2plopnvup.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2zuokomas.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2wstqbwsj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ywjvobab.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2oohaixed.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2blyizvcu.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2bilrtjws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2fjivydej.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2uqzhchnv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2xvoxxkab.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyvldzwm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gt2gpjqmqrw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gt2vpwwivcw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2clbqduct.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2wekwtcoy.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttopejvj.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2cimxblnp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2tberinbi.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2osypthqa.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2anryzzpp.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2apjnotwb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjjqvyfz.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2nzktzmws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gt2kogzmwtf.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2mnyxbcmt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gt2wtpezkzs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2gjspezjb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2cekfxark.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2gkfbntek.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uesnkeue.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2iitreinb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2fqcljlcm.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deijvgzn.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hltmldfr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jottxmos.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfdtyysq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2axnxayzb.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2hlasdksi.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuedqdwg.html


<!-- 参考信息 -->