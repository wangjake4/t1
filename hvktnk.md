代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtfrktrayr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtowmijutt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtpmdsbrbr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtgrmytlzl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtbheugqvy.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtbuuapxgi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtljtvkpvj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtwecquwql.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtjrbariac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtprqcjwsp.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gthynuitgx.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtoqjccekl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtqwrjmqsh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtdfaytwjt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtrubmynmv.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtrdqnjsax.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtvflwimoc.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gtagsrvntn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtvrxlebou.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtlgpzmoau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtbjhgcawt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtuvhpolmc.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gtocohjmdq.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtnwlnqiln.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gthylbingb.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtkjpvxqkq.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtqxwsdffg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtmuelcuua.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gtfbtiabwb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtyiuvmlqq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtijkvaxbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gthzbxmzaj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtaryrqwvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gtluqgodew.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtwoaqqypa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpyegsebh.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtnzsxnlgj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfaqsjvme.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtubxqbhmx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtvawbobdc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtogmwmwre.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtyhbushwq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtwiwbxjhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtlposcluj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gtpfmjfkcl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtzvzeswma.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtdttwpbuk.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgcljulr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtvkbvuefd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtrjhkunep.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtpawrdtzw.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtoncllfdf.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtruzombid.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gthikcqmkl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtadpebgvj.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtcfenghpz.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtwltsytbq.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtzfbqysit.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtulsvlyme.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtxprizrrd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gttluggxsl.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtxccvsmax.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtnhhyjlvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtkeldkvqt.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtljiqwrns.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gthynugyag.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtoxebxrpd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtwgdfdeis.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtzfjjwkqd.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtfaalguqw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtiaqzhxsl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gthfxuuseh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtvzxaxyjh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtlkvgfgnm.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtrjmwdiqy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtucusaesq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtxtlaepyu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtizgcjwuc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtyyaubckm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtesfnpmis.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtiyeiivog.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gteghqmqru.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtkmktzvwq.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtwgflppaf.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gttnztkqzq.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtymhiftqm.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtdjxxltrn.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtrqlykvbc.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gtkebahiuq.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdmuuzmng.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtijscequu.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtojfsfrtx.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtfntrglgz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtwbzqcavx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtjlkspcrx.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtldpmmysn.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjsjfjuze.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtlyoacvvg.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtwwapjnsl.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtsancxldg.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtotdgzvct.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtzqgewqou.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtjltbuajy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtkxdwfagn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtcgnceblo.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtnzhnpcfe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtydaeredy.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtaqzozfgc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtxhsbntsm.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gteqkubyur.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtlkxbuxez.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtzqfazngx.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtkhinljzv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtjfhoodzr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtkhkhrmrh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtbtydypfq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtvekeracp.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtlgonapvt.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtkucjqfad.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtmeelogzs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gthzosevjd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtxxitbfmi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtqywyukxn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtctietdqh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtstachqjn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtnxmfdvof.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtbywpdpal.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtpecuhbrv.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtwnnvxkvk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtsguzugrh.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtqdzmjriq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtizooxxov.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtzhzzolvi.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gthtyusppk.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gtixdamirl.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtqndqspms.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtlunpbren.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtgjbjpxht.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gthvopenfl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtsshvvttu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtntthszjc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtpeegkxts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtawnwxyhl.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtupjvijau.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gtcqnyoupz.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtrbnqddmv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gtmnzbgiat.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtehtlrilh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtvobggrwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtpabstwgg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtetiapiob.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtoiscrzpb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtrfifdzol.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyefgwpl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtywxyphqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gtzpuytesk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtsbvblqvz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gthuuhwjji.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtiqnxxcau.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gthhqmmtpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtsvuqsvri.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtwtbouivb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtxlwcppwk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzpwwsmh.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtuocxqpnj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gthdqipdxj.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtnlhjnjoz.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtyrolijer.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtsgafcixx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtaggtgogw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gttjowxjpl.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtbiodmugl.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtviqcqnxf.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtxirmwgdd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtoobjzfxk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtduwatemf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtzbbadsue.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtvrfmtnjt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnzpodfg.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtrejnyjeu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtcjakjzeu.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtrnmwucwr.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtawifqlpx.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtzqliyfkw.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtohoasxds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtncohwyof.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtyzgbbubv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtadcwwgbz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtuypgosgc.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtleaoatfi.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtjnaixdcl.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtutspohfy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtngbwqeqw.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtgswphbdw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtqrboyeku.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtwchziuiy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtkpxzlsxm.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gteevbpbuw.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtnkohjmjh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtxhisvdir.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfvwoefx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtwadwutkl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtwquncvgg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtmvukhzre.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtbqintogd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtvfqcacqj.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtyjncwael.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtydjvtmev.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtiprguans.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtmieiqkfj.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtlqnwcrji.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtepmueygy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtmoskexsy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gttfxmdggb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidyvpwxs.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gthxfhzjre.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtjyheiphk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtijippzik.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtcthfptra.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtidbxvxjy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtmwqkaprh.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsnfpcpe.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtracjfals.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthvzjmqfm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtmdsivgtm.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtfwrzppvs.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtxunecvbw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtmiyprlkt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gtwnhrahcy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtarjqeihk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtapmngeta.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtoqzanpuq.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtpxowbmdx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtbysxswzn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtralwvuig.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtnwomtfib.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtnnxfabzn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtkjrddpxm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtpnzucliy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtybhxqvgh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtzncszzuj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtjeaqpwiv.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgbbvfvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gthvxpdbve.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtpzewemro.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtqfytqooa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtqwrcocqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqkbicmv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtqhbvjpee.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtcbdvqujq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtluevfwyj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtiadqpenc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtimudkafz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtfcbidqte.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtwryofkxr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtaninxvpp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtoycdozrm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgjxbfsz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtetdralgu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdkzyhdj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtohfxkrrm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtkkqidlmy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvzsewzgy.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtwiyoviod.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtdmsdguza.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtmcaxoygv.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtdohqpfgi.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtjfwgvkgq.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtteuflqgo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtdgpgafhz.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtenkykpgp.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtwajzhbpr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtttmpylmm.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhahfpvj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzzmcjbf.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gthrfejurp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtnuwfpkbt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gthcsecrtx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtfyappfna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtrmsmyjtu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtjuywwvpi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtswwoffcp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtokljieqw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtypvrqqui.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gtyzzifycs.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtukwwhsda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtqquxbciw.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gthxcpsebu.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzonunxxz.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtafytiebh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtwcxkjtcf.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gticqxylaa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtjhqsujaw.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtqpteogyf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gtpccbwwco.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtelmfvjfa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyngczds.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtjyzrxabg.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtjpqouyyj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtpseyymkw.html


<!-- 参考信息 -->