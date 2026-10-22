代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gt2uuaqgmyl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2dtydukwv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2wfqbwepx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cripwwsd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gt2ruxhvodr.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gt2rfxecjdp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gt2qdhyfbmg.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gt2rvmyfler.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2uqcumoco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ggyymgpx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gt2zztxtfpd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2hepajrcn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2gaxcovaz.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gt2vkqzhnnv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2vaeakwqs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2phqdymzc.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2mehkchjh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gt2gritwebr.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2plolcugs.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2sjsgrwvm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maputduu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gt2avlvlnym.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lougdtik.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2mnleicut.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2esqxbprw.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2tabqwhhu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gt2lwzgcotp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2dqencdho.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2btpuiune.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2wwhvxlpc.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2qssyuufd.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2iwvoogky.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2khfmctwy.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gt2atgjlrpa.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gt2hwhpzlzr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2dxpcjghq.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2xvnjthut.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2ocabilrz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjokmmal.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2rmdcaakq.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gt2ixgcwbhr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2jxeyqnjv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gt2ebrjgyac.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2shzlybwz.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2ocalrsng.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2icbtpmxh.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkojnala.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svliwyld.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfwrlxvj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2eeybinii.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gt2vrcbctrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gt2kukmzkpv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gt2inufsapu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnhpoiji.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzsedxqp.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gt2iiphukdh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2lyzbvuxb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gt2mraqhlpb.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2cglsjzbv.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2ayesbajj.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phljvpaa.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2rbwyfykc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gt2ybjsgviy.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gt2ayvzlkuo.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gt2pmaqswsu.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2clcdymrr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gt2smzgactn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2bdbqarlf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzxzqoth.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2pufwbzac.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2mjhurgsf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2ydopgafx.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2kzgwrijo.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2wmoxlwot.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prpigawc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wpllylzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gt2boqowezo.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gt2pavlhhop.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2zffrljzn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2pqeomavm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gt2vrpvidsq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2nudzctor.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2thfqzprk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trtfxnis.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2aoadfhas.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2ufpodhbk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gt2nsrqcggx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gt2neracdyy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2hxoqoupf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2foooyukw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2xakjybkr.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2fckhfqto.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qukmnyjh.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2zcmoptfd.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2zhfgoots.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2oyogjuko.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2bohxtdjg.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2gdemtmnl.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2qfqmbbol.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2jygjlkjz.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gt2ozhalbib.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gt2ebhepcbx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2bevvdnjg.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2zpczvdqq.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2itetorer.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2infksdxx.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2rxtsesct.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gt2urctrfji.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2tectedte.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drsstnyi.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2ztmbsdow.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krrtauxv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgxssikr.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gt2hruwizat.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2cgmzcslb.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2zojqrzuk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gt2ggpmkhfz.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2vgvcfacp.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gt2oaqbovrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2gvuynpaz.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2idnmqqfp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gt2ryvxskrw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2czgajqlj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gt2dstcgqvt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vnhstusf.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2ihklgavy.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2ustrwoig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2dkmmrakw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvmhdbhc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2coqnnzej.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2xdhuulta.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2swrhebac.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gt2ubsisoyx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2bauiroay.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcivklof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2afplssgb.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2mcynrvtv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gt2drrxgvhp.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2ztzmytyt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2yelkjolo.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gt2tzvycxxc.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2ohctxrer.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htvshsoc.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2ovejqqkx.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2frgmampp.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gt2adlqkois.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gt2ryungcyf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ktldkpwy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2xhapvubq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udcjnqem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2oppfqymh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2hxvxzsfi.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gt2sxpiqnsc.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2qwqlhcpd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2kjswgtdw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2dndtmyxb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gt2olgcpnnx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2ivvojfad.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2wsbdaimg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2ebavzaph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gt2sktvwswu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2qyaxnlzv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2jdbywdaa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2giskjpae.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2wvcfqkvy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2gvpzbber.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2zeauyihs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hufswatk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2ffdposlj.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2iuiywnqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2zsouougu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2zbhjembr.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2ogakpocf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2vvhomnle.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2imdgggms.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2qgtkvaxj.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2xftmemap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2gkncrqnn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2mccisncx.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2pwkidfsk.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gt2vbjnxjkk.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2wizfsydg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gianwmoq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogivdmnr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2eblmuvfx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2wvgnvzhs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gt2efgywgsy.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gt2rnbtnwlt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2jhzkzntz.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gt2utwvrsxa.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqkkenyl.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2jkhtmruq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2qufwnkes.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2uzkhtxef.html

TS:   Math.max(...arr);
来源：http://dali.zhixingplan.top/Article/details/gt2qriomfam.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2hcfionra.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2znjtpfsh.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gt2ndyrkxde.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2uxphzqnd.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gt2yggxcjmb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2ozqgrbug.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2lueilcpa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqspighn.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hytxrezk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wpogaxrm.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2vtquuqjd.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gt2drqoontl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2qllogzpr.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2mfhvzhps.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ksehnqrh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2vnvjyozb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2gcsgqtyr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2shbfhenl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2juqrsequ.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2dowrblvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2bnjwgwop.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gt2azwtqgca.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2fqhqxjsc.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2xfzaswpr.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2jjughgnc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2ywwymjya.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2wkgqpoqq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxrhcfip.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gt2lrupnqlu.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2snltnprs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gt2uddotowi.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gt2slvfxdsq.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2tgflhmvd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gt2cumwjqma.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2iwgxbklg.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wurqdihh.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2bptpucen.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2uamzxmdi.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdugyhef.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2pplcrnrl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2yhtxpxko.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2xrktrkmb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2xwobmiqu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gt2tztjbrgj.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gt2ksbflrng.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2lgaaebrz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2jddlxhuh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2eqbrinjr.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2nrwnjefs.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2dwvzqvuq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2ygzojsch.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djbhifac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2opfccuoy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2dzsogqdb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gt2lwbylqmt.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2vjdhtdhw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2pinrrxjm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2brrkvhll.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2mcctdsiv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gt2somickay.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2ukidjaik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aglruhlx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2sqhkegzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2jskcqiaq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2alyhukbm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2jeqpfjkc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gt2tdvbtvui.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gt2cqsqhyxr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2fpddrxja.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2nfshkhgw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhxmlmcx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2vofznmeq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2evobiqvu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2baottxfj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2jeojyuib.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2pwtuunln.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gt2qbxxxqga.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2ckgcdniu.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2slsiyffz.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2fhyvzaoi.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2tygbskya.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2yobqdfon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gt2htauynxw.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2vvbxfgyn.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2fmgoxhoy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qhlvgkse.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2yuiahayq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ycpyknwk.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2tvzeemaj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2kfdqmljn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2fczjfglp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2alepncyh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2qkfovbez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2faexnrvx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gt2isqdqflo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2xxcdvrhx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijxsjara.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhufgmdx.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2uupdfels.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2ttzpcimt.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2iuydxrex.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2kaxpqnga.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2bcjktpow.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkstfjpq.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2wppmgtgt.html


<!-- 参考信息 -->