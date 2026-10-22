代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbchdwvs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cagxtnsd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2lrdxsrup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbnkrspv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yncodyyn.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2lebanzhd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2despalmc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixerctsm.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2qujwlwyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gt2scijgirs.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2wqswtfbr.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2tkhbxmxn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zdcmswfl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2ermrrprz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2egcjpymm.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2umcktmmy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2smmiadwx.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gt2izshimwa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2uiieelxy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2bwgfnvfs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2baehuibr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2epvlntyi.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2vpjjixqi.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2skdspkrx.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gt2jivqgcdo.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gt2otfgvhsu.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2kopzbtle.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2srpegsfi.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gt2arexgvch.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2upnizxbl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhbkyhbn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2untzivup.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gt2ycnmvsvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2klitflzc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2cbjlfszl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2oxkxoezp.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2ifbrivlm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bwjrklio.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2qsoferkd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufzsjtyz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2upakwtjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2lurlnqkw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2azygsexj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gt2dwgagbtf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2reefbabj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeqkolbj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gt2qcretdsc.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gt2savlitge.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gt2iequkeiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2erwxnzch.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjwzteiy.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgvtozbs.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2jkypbecg.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2xbsjndbm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2fxuxnhzt.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2afxfcygk.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2uuvzisqq.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2fphlbuso.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gt2uuuvnhjz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2ukgbaqya.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyvfikij.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2gbicappa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gt2zqkpqult.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gktygbyy.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2ueykicmz.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbneppxi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gt2nyyzolev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2kkyiyhft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wubkkhtu.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gt2qkfenqli.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2jfwhuwfa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2vylqyheb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gt2ifcuxexp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2olqdaoaa.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2hpmcphmi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2gzjxzaax.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ondrvyvz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2anowvicx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2lbuxirik.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gt2fsxkisso.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2oqkduvmn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvxkqrzg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2dxjigcqn.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpgocqcx.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2cvzqbyof.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2vyztrhch.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2dsswnvmw.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmaqjdbe.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2mkvqbonq.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2qqijzknf.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2luethogx.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2abzumbqt.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2okbcereq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dplmyobi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2kbdufepi.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2vhrkraoo.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2sdlpflql.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2kvsqlsqj.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gt2yylbnynn.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gt2szbfbxuh.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2aepyjsrz.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2bepnutot.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gt2mtdksrug.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2zjfmkncx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gt2xilgbxwa.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixrasijz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcscreui.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gt2vekbwoaz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2xwzbatjk.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2dpogpzyg.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2efzdsvca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2noqntzrq.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gt2tenakhtd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gt2aergbphg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hppyunni.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2efypndad.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2rmlxefmk.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2ysohpypg.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2vifexzqr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcroimxs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2pxheudxa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmlrtnjg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2jtxlfqxt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2etidxzhl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2nqxcohgk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjbzojtt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gt2mmxmmgsb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gt2wnvlpoio.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2fbjqrgwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gt2wvnjljdr.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ddpcqaip.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mydymvtv.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2qnuoxvtr.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gt2mtqqoazk.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2gslooirs.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmnjklzl.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2vgmwhdky.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gt2errrovlo.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2qstsknsl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2piyogurx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2odcznfvp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2jxcovaib.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gt2zuuygsvj.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2odxrlvil.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2wwhzwwdd.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gt2xtcbgwhf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2epfmyinn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2svowsxkv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2enxvvjau.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2tqpwqikj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2dinkcsvo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2ewinxuva.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gt2nlrhijpq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2movuvrqx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2maclqohc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2ucrfuhxi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdinzxqi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2jcensofl.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrxnoqpj.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijazmbam.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2ndaojhmy.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2nlxvilgj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2wrhvioqd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2smnzowzb.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gt2afeorpsb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2ocmdrlck.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2elrvgdwy.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2ytmgvfmv.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2pnuafcah.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2srfvwghk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2gjjwlfiv.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gt2xffslmtk.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2inbyzwia.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gt2yrhsutrp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2qyjdcink.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gt2qvtfcwuv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2yyzgeras.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2rmglacau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdcdphxb.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gt2hgvcgpep.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2tbzibpac.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2wbbsnnuu.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gt2bbussbtw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2oxxvktwf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2biaoexip.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2cgzoxemc.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ochxcmfs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gt2phmphfrm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gt2xmxclhme.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2pmagwtqg.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2vhckpbrm.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2qerunuqj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajpzrjlf.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gt2yobvjtux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gt2ikhxpvkd.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2tvjvmtpm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gt2roowaoea.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2hjzjmqto.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2lurlgjpj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2tugrvsbe.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gt2oynstlxn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2pdbioclh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2pnidpvaw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvjanlbv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2dulergtk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2nvurmhuq.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gt2rfbpkkxb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2gdslyemk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gt2maodwyai.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2lvkthkhh.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2gmipmedu.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2hardmyab.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2jipekoij.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2wqgethyg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gt2ivcsjoqg.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gt2hhwwntok.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2winqwgak.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2mlowzpsh.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2revihawj.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2fvlpdsql.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2seogqtio.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2dgjhrtza.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2hzddnedw.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2evvnozzs.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2exisytoq.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2lugwpvzq.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kctayfng.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2ttpsgsvn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmoecujc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2xmbxituc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2kazwqedb.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2hfwqlaxt.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gt2bqbqfsks.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gt2dnklcdkt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2qvmwbupe.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2lefawrcl.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gt2deurjlao.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ocwhcxvq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2sipdtdmq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2avkuouoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2ysbpcrpi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2fsvlmnsy.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2vuthiaip.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2sadvledz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2qqjjsifu.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhpabqun.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gt2zbdavzot.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2tknpfsvv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2wvfvwvhd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2njrvdvcr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2usazujts.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gt2yijumuaa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gt2rklgllxn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gt2avqaddvp.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2krfrjvsu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qagtadwv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2koldvutq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wkxeobwn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2bsodjcab.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2pqxbmntf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2svevuovx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahveovbz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2imlbdppm.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gt2cyyillvc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2yocmxpcu.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2htgnmodb.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfqvkoxk.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2atpfocac.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2wghxrrmb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gt2ryyodrph.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2mvjraaey.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2xfirkpaa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2efvzyxlb.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2nepxhikv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wwlzxtdq.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ltbjsdpz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gt2fqjcvtlw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2iftopeho.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2oyhxwnji.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2neuslhcg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2yriemqbw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2ciwalvkm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2tuapqmzu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2gbbyssjo.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gt2jdztxfry.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gt2ieyohrvx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2womqogwd.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2vsguwvyg.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2ivfeznul.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2fdyktmgp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gt2wwnniopr.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2fnyskauk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2imsvxvaf.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2axxicilc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gt2mkwokrco.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2veydpdeb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2uryisbek.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2kbdibenq.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2rwyysppl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2rhrbehen.html


<!-- 参考信息 -->