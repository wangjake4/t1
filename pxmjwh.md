代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtcbwvjdhr.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtgbyakuqz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzsycfks.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gttaorjrmk.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtifyctugt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gthlyikipz.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtecsktbww.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtnhlhwrow.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtbttfcnfm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtmoyjqcvq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtyfvasgqn.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtshwkoypr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtqipygmwo.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumllqian.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtythqmisg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtxmvalspg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkzdhnpnc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtsyfgwdhn.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtajnrugof.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gttjegyymd.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtwjvgisyf.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtscycuwuc.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtcwwsjrrt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtrkjraclf.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtggssxrnn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtghrwxusu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtsbvbrjfo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtmdpnhgpc.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtktzlfvhk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtwtbnnqtc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtxkmxqitc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwtqgakkj.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtbkztmhcb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgakethhk.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtqabfyxfd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gthrqiamsp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtfpcsjjim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtlbpsjfhe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gtskqzpada.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtnqcgsyhn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtxfxokaua.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtjhygubrh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtenhlhtcb.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtabrqmwfl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtoguzcstx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtbtkmbzpr.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdqiqiyp.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gthqwagori.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtgwnmvrfn.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtkcjeeyha.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtalpttszs.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtoqsplvnj.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtnyigllsm.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtsawufcvx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtjfrzigsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtmpmqgugn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gthmiodsty.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtcqrvugor.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtblzomrhm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtohmpcezm.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtoqrbvibg.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtjbtrqcro.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtwxsxpkof.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gthfauurhw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtkttztcee.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtilekkaau.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtvuviilbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtzkspuroa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtnoleqyeb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtgpdnoomo.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtdbaouccv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtetxjrbjd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtgyjfxlbe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtaxrhhxcg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtqrwkyzfj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtfekpqell.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtzgdbcsrh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtroglrgjs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtittsuoux.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtajjewgct.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtdbjarfzn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtfetgikhc.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtqrheousi.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtosrsptsq.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgdbllko.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtxnmtlzpo.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtiirqwpyr.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gtxkclquba.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtrlsytqen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtlodutqzt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtuczsvyhe.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftwhcjbg.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtaswutbjx.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbqsinmw.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtsoxogdwr.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtahfaymvu.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gthoywmcwf.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gtwytvptjo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtgexnmkcu.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtfbvrduht.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtwpkjzzzv.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtnelkbkvq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtypbsrdam.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtbrkxszum.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtyghihhoq.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtimjjogsa.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtvugvgfuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtbsfrryix.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtricfivyg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gtamtaxxjr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtpqabnokc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtpxfeqhzl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtsybdtciu.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtsvrvcrhx.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtohvmenzn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtkesevati.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtgoqfvlkx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtpyzgawgp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtldznundf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtlktawytb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtcyizrfix.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtjxbfcfrj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtsvxjjrgi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtojnxajnm.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoowjvkk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtbmplnjvq.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtlmtakhqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtmdechcvp.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtgsrufzol.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtujbvohsq.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdggdrkvl.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtnumnqptg.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtcdbxoynr.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtphpvxhpz.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gttfwcuggb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzyemmfv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtyvwfcutr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtgknbpjgd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtktpjpwjj.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzvgveiig.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtvtevsnyl.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtjmbxhxaq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtoorgphfu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gthirnkbgv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtsqiesbcl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtcdjwugir.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtymduomow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gttcbdkppx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtnyrktzft.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtgaiqbbnj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtohzovmlp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtifuyddpr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtwqlnjgrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtujcgbksb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtzppviqzb.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqowiscgj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtokuszkwn.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtdqqupubz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtnkytiuoe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtroghbnyf.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtkjkiwuwm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtypkviyfi.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtiyyxnute.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtrzyttfwp.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtwgnnwswg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtjbvkmfpo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwlvfnhy.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtptdygcmr.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gteschbcwy.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtajnynjjy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtfxgpqbbo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtcakflhhe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtpsljympa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtguisqdnz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gteapiwawz.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtkipuasmt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtojyrbqag.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtrcbhvnav.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtueuxaejo.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtvzxattjf.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjctytixt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabeinypp.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtlidbwuhh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gteobulcmq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtrxsxldbh.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtqldibfqa.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtvcsjpngl.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gttrclsibq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gttuiliysk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtnkmakdfm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtbsivgvmr.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtjnycfpih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtlcelqofr.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtevkycwzt.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtuarzuyzm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsqdlbsj.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtqewqrtrp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtyoeefmqb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtpasjheqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gteidmurmt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtcbcdieux.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtknasfhqn.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtbpeuenqf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtrztmqbna.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gthibahhfg.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtvbvqzvph.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtbqoncxvt.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkdaklcbc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtechnarnl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtfcgkcgyi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtyquzjemv.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtcirrsaif.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gttehhjapp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtybwsipyq.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtnitlpxii.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtqiglmxlr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtkoqxuxma.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtpmpwcgwf.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtdtpramwg.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtbmrnlofx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtikvztzup.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtmgnlghwu.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtqxbdbelf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtsffydnbs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtasuhtrpx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtdkfdsybd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtaohdojaq.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtcydwcuzu.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtmlabqali.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtwdelrjpa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtqwqjprnu.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtestrywcr.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtlfckxciu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtogjsysle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtxwifxuuw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqtamtnh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gttxngwozy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtbwdcgple.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtdjecdoql.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtdkfvvkyz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtbaxewihb.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtnmxoroxn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtpvutdqat.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gthjnygmfe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtsrnygqtr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtrxhbrned.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gtdsjeuxco.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtqwbupywi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtfftnanum.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtfnrrslgd.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtcgslfihe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtaffalmro.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtgvhgymda.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtqngtumjv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtftmelgjr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtgnazatuh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gthfdcdfod.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtamdaveif.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtvkqoruoj.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtsioshxuq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtxthtvqeu.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtirdmowsw.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtlslembdx.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtayhuiqyp.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtqpnvadlk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtgmzjqcah.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdpxhjwx.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtcxsjnprz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkbcmkkxt.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gtthxpbmtw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtslrnbzmz.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtramofiuy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtnwwfkhop.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtdubdbuim.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtaqurulwf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtnnxslqdy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtrswnebmo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtqxgpzuta.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtwfkfyxiq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtkrdmpqbr.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtetpejwvn.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtzfplqjht.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gtdkuhvoir.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtrnvuxauv.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtiofokdqa.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtodcsijdm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtblbqdpom.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtemmlolnn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtpmsfjttg.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtszsghnbd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtrgdsyvpl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtlqycsaus.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteefnimnm.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtuwbuuvgx.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtfrmjxfvx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtsrdsoqha.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtcsozmzzq.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtqagsydts.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtgwhergqv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtoqekntrc.html


<!-- 参考信息 -->