代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtowfifezd.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtdlafomkt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gthwmqhrwy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtiswzjkrb.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gttdgoxzhg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtsvixgusx.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtfkjkixfm.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqulbbena.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdedrswy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtxidldjgg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtzyiierbk.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtljidhcxe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtkmptoxos.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtskeqsoos.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtvwdsbwkq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtzrndzxet.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnsccpjyv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtpcibrdxv.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtgxrnkget.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtpgadvlpj.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyyywzph.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtghawyzpk.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtukwdflnu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtfmqzjhae.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtjmjlihlh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtvenwpvov.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtgvfifkvx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwujnoez.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtvqfyzqgm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtykmhcmqb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtqxtsulsx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmbashpfe.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtgxcmuvug.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtalpywfeg.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtxeimojfq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtvzlqvhdr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtbpyjahnx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtykjpkuac.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtxprzyxqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gthmbghcqq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtrchviahg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gtcowjlyue.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtnxwfefwm.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtjsdvmyxt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtpiuymyhs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtdjusnclu.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtyhdeuxwz.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtlsihkshz.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gtwspfftvx.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtsiebimge.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtarcifglt.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtomnavzlh.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gtjxjruhxv.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtjvtglcey.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtpydoovmb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtniqraxak.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtzkudhrvi.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtqeghbxeb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtmqibcvuz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtfirglnhd.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtignmftkf.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtporuzbha.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtqltztloi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtzylsxceq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtojckfkyj.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtgfeuxokr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtahdtgklm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtuguzfwuz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtjvlqwekp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gtntlpmobn.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtcsishbgb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtobnefweu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtaokbsooc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gttrorbaov.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtegbkykho.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtdffpqxdj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gthognmckn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtdjquyyri.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtvvvsqffv.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpggjyptm.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtsflidiwy.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gteptaiviu.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtdxfoiotq.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtyqegvxhu.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gthdpdruse.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtlnzqkcys.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtbwcejjwi.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbshjnst.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gthidlbcig.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtbuxaeimi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtoslxtbiu.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjmgdmxeu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfozoxffh.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtzlvcaowk.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtxypfeuqs.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtwoctmhyf.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtjxxxvgeh.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtkzjffeqs.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtmlgqjrgo.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtkjugjiqi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtbfciuupo.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxjqkqhf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gthejuzjzz.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtwmlvyaqg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtxjzklgjt.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtvivlcsul.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtpveaqvsg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtyuyvmdjc.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtzdqjhrej.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gttpjduast.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtvqpohqft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxispyvx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxahedyqz.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtloaywirc.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtclymfmws.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtvvoklhbe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtxygzqwux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnngknxjd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtqsikyads.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtzffrvisb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gtxxukrfay.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtjscwhyqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtpmssomii.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtbinvjwzm.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtvvhphrbf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtnmjewifm.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtsmxqvdvw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtnmezrasr.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtzxwaefvh.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtjcnuqeyt.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxlunwarq.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtfgxcyxgs.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtkoumqyvj.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtithbevzl.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtcfhagmol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzktpxovk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtgtqwuqvo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtnpxpbwix.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtlpnecrve.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtbijtfjqr.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtsgudtpql.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtefotmwfh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtlufemonk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gtinxdcpud.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtwqqyvkaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtutanfane.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gttmfltdjs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtdcncthvs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtvvufvpmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gtbkylcazt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtsgpmkfuj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtbyfpfgyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gtyhzxruov.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtyncxqkkj.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtixjtacyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtsklmpwwn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtscpblerz.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtmvwbfmlz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtggvoqykb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtiqumtqfb.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtqzygdzcj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntccgsjp.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtavtaknmx.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtsuzlimcy.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtuwprcmpc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtvjpxsgad.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtwyyrvdyf.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtjtbwrvkb.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtyfngfhbf.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gttwtvugcm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsqqczdy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtrmiclivm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtakuzcjmj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gthnplonkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gthnnlgsre.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtworiqapg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtwbckmbjn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gturvkczzz.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gteysktkey.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjijqqjki.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gtjijlzdop.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtzhovgvjp.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtmanguwtb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtrcxhmvvo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gttnrxeymk.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtwmomfldw.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtchgabbdt.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtttmmrkpr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtjlaunbrb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtelbcwhek.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtkfoqehuh.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtfthbhwsc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtxgkroruo.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gttjbookzg.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gtmikayxtg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqdyexto.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtrriqxdis.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgzfgvnuc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtatljaqtq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtrolmdbvz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtqeblskrr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtudcejwqa.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtcvqymroj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtuwwjtpmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtljnusitc.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtbpxqimnz.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtjxvzurtk.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtuqzgaxsx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtlbaqndln.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtjsuhgpmy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtjsyscswo.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtmnnopbhl.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtqnpejgyv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtkpeypbjq.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtylqrsqpc.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtrbbliyqv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtriogzgwx.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtlcdqyuit.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtzpvgrrqb.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtifkeixzj.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtmbzdexrk.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtzedjcaii.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtkxeizllo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtspdntfqq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtyuqyrwjm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtlfxshuyw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gthlcbgheq.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtrrpzdhud.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtxiyekjwp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtbvvjlalw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtkgqgadea.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtlujkzemo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtjzslmdsl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtzdhrsfbn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtychcynki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtbjcndsyv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtogsavpab.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtkmawohrd.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtnoqrmtoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtsdrfeehh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtevocztxx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtjhaltkth.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtrjjlvesd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtmayelzjc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtxzmmucly.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtiziegqcg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtoftlkppm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtlzyetwyi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtiplbrihd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtbnjyeizl.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gttnsilsra.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtbiaecldw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gttniquzdh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtvfkksf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtfndibgut.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzegozbak.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtcsddpvcz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtsxysrcec.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtwkztyhan.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtoiospixu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqkfwbee.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtlqvtnhpz.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrkpgeld.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtxecryfta.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtucvckrlq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtmhgxycod.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtptnqzzfw.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtbwrcvawg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbqwgtcio.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtjhcicait.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcbksvabt.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtkbllwivw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtxtzuzgmk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtursbrtnv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtptbktsrk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtcrpzkkzm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtzoipxvjj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtxtgjpjvi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtpullxkcs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtqaynbvjc.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtjiddcfrn.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtvutqarul.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtkmqukukd.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtwkfwipoj.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtqpjtglip.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtnqpxzqbi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpiddqyj.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtjlpmpprs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtjfnqzsvw.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtjkusqrng.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gteuqsrrby.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcljesfej.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtqeksoscy.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtnrrkggee.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtphckwkpy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtcqworkri.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtjthyikcp.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtkylcaqhs.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaodajgtg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtriwyyxha.html


<!-- 参考信息 -->