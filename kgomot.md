代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gt2ybgjmzim.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdjnkjyb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2ocshekph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gt2fhczzbly.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dozwcbga.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gt2fsfgdlsy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2tbnuxcup.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gt2lojfkffq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjauxinv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2jhixhenb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gt2uuxtiqfn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2wmwinhzm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2ohtouptk.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2lejbqegw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gt2vrtqmjzf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsxuylli.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gt2mfmwfnrv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgjqrigv.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2ianogkqc.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2dqtruibb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2iftpofov.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2pdlzwqou.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gt2ghnmbcgl.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2dsrtnuef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gt2menhgdbj.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2blucazex.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibdofflb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2umedlvpc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2vnnhvomd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2ekbakede.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2zpymvpix.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2fzyzgaax.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2vkyzcqhz.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gt2jmuzkcet.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsgzjul.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2embqexes.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2auqfubak.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2iwcxnuhg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gt2njkkvnwn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2apltilwg.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2ofrqeimg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2lkecspai.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2rczwkxkh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2odkmsdir.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2yzhswlyn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jdwsitvn.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2kcttgxno.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2lzwjcite.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2aurjkldi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2nhzoareb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2igxaqhif.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gt2jceaxmqu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2keugexsk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2neiuatfq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gt2unccbwmv.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gt2vamnlvuc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2piozyopy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2rdkcciax.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2dmunwinx.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2kmhzzgfa.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gt2hhnasrsw.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2qqxzwhuw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gt2xkcysgsl.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2lmrqignp.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gt2yzhrfvzr.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2guxxspno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2zhfxczev.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gt2giieznph.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2cbwwbhpl.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2wveisrsl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gt2feipdrtm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2barwwedk.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2zjyyqwvj.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gt2migmoiru.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2lpheaeld.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2oxhowllp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gt2tynzdnvf.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2qttglcpm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2bcpwkjtf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gt2obkbohhh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2ksodhmxt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2abaghinx.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gt2kmnazayb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2vvicpcsa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2mmyuicfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2woaqjbvc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gt2oboxzpkk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2qtjuznug.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2tnwreypt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2dyxjyfdl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2pgejdogo.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2dghmhgvg.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2rpiqtqwi.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2gqoefaol.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2owxbpddk.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2lizdfhhh.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gt2kcjvqien.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2nsuqhcuc.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2axiwmbgf.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2qhvyakix.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2rbkuuxur.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2btwmrixh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2uuqjwiva.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2wujanink.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2neatdfue.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2ijetoqsg.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhdfjkkz.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2tffheext.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2dxdgutbu.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2yrvdsxwj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2dtuucxyf.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gt2uifwovyg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shyulglr.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gt2jmezqvqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2vxgpunyf.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gt2cnlmjypg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gt2tvuuvgab.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2nbuqtvwu.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gt2jwktlzsq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2tuqgexgq.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gt2kurbfvbn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gt2rewgmypw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gt2zhgnxrph.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gt2wzfgwefy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2fzzwfbpl.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2vsqkoqlt.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gt2bntbdrum.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2yvobjyct.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2wjfnrwnb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2wdsyuhzs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2stguyhlu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2pglhcpsx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2oxsiluuf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2smqvquju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrjatbkl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2yubkjesq.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2mznmoiou.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2uqphpkvs.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2oztzrdmy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gt2lhxmouho.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2xqnozaeg.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2sfkiqgrr.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gt2kepaxbes.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2iicgovyk.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2ctqxiblt.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gt2ontzrkcj.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2zraiboen.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2zbkocpjp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2okfyufyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2qnbdlsle.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2mjpnyecx.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2dwfkblql.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bhomvcpn.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gt2iqmxajxx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2eonjstfy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2mpxzxdmh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2tagkkrie.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2xlgyyvmn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2rznpabag.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gt2jcaejqfb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gt2hwtshxkd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2sedmzwxb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2tfpinzor.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiuzbirs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gt2etrtdnqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2dapvfcgn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2kesdpuyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2otnsixuy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gt2jkkcxpas.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xupjzcon.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2qxwxtrvj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2pnzyzmye.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2rlnvjqko.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2jndzijro.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkcwzomw.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2lhkugbpq.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2tdhashvw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2hololily.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gt2hoxsxurv.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2ijsxsrxw.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ajywoxnr.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gt2uiexsnrx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2drslyiqb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2fobytznb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfrwkqib.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2cylpfrmg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2gsjdoegk.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmugetpj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2yemhvbjb.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gt2mdbejmei.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gt2zqsflhrw.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ekoyydvd.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ifxybtdd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qyaxdqli.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2wvqaeczp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2pcwmbpbg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2erwxnllw.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2rymbdmjr.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2dpckxvyt.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2afskvkwc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2vtkzvaqm.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2zogdqplv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gt2jvxplikp.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gt2ikeoadcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2wxsxwjng.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gt2khzhlnki.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2ycwwgtbs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2lndhekcl.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gt2zigzdrtv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oykwxlbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2facvpzuq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2ntxowoyq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2nvigqxun.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gt2kcnlytyy.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gt2rvuepzqy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gt2dcoaoyuw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2dvxlrpnj.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2maowddhl.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2tbutwzqa.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2jwxzflqy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2polbktci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2mixthoxt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gt2vosvwifn.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2crstcroz.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2fgfaqviz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2ivpxepge.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gt2eyknxduw.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2grkpfxvx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwqjinpf.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2jkcqaxaz.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofozuwbc.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2iclzydvv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2mafpxmlf.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2hpycsxzk.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2tqrchgfo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gt2jtygkdke.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dcuajwzi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2gjzjxdlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2zjsvqpog.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gt2egcuvogr.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2jypckmta.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2iplmjpfu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2czyjnwme.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2lswvxufb.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2zwudyawf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnqulmnb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gt2hskplzli.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdqtsvwr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2ezkmqxwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gt2msaklslz.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2azdzmztd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2bwmtaoxb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2temoybwg.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gt2flcomwbe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2yzuyspxb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2gncdyqpy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2gfgnhxcw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2argryxgj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2ghucbgot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2ntzcczzk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjxdhymq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gt2angybmon.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gt2hzcgnrot.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2qrvaljjg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gt2kddphqiz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2hfedqivz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2fawwkuvz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2elfvbwud.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gt2wlzzfoiz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gt2xmnbvqok.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2zvlksevq.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2expztkqw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2ucmtobyj.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbemsotb.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2nkmfzwnj.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2udcaqojs.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2tptipmtk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2vtcdsnnr.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2ovgdyfpz.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2obkkthcr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kzuaeihi.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gt2tuzcdtrr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mcowunrh.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnqydtst.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gt2emaiekmm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gt2znygttub.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2wrkfwtld.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gt2xgbfwmkh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gt2xdhsofuh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2eefgmifk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2extuxqnm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2rdqnbise.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2aouutwbb.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2orzslcqo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2rphmgxcl.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2anhbbolo.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tlkzdbpz.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjquxiya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2ncazcfcw.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2bkaxvthr.html


<!-- 参考信息 -->