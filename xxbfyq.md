代发 wailian999

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtlwcqimob.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtgjqxlraz.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtnqqzgqea.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtwbjwmddf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtpmikajtk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtrblymwsr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwnpxxmi.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtttwhgmbw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtwhyblrnc.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtfjaqutsg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtjnaolglk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtuozfgpxe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtwtttwuec.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtjzrdmrmy.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtodjcwqqb.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtjqpjmgbr.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtddwdgske.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtfsqoektn.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gttbzxdsnv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczwhorrc.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gthrhquztw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtarfstnhx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtnrclzpmo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gteifftqis.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtjbgcjjkl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsjzkony.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gtvrjdtpih.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttfpvvwvv.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtblrkeukr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtymqdtxnf.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfnjskfc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gtylzvxjrs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzldmime.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtzpwxrfzg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtbqsihkeq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtgucyldss.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtypglnqmo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtgdbnmuxs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtyslyucsz.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtsnagpquk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtqpiwmiee.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtwukwyqkg.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtspsrdqnw.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtgfnuuuts.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtwunwamow.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtyyfttdpl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtpkaspbzw.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtvbhwnlmy.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtjoabmhza.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gthjedctcv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtevinuean.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtsbmhjilp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtlitzeudo.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmllqytkc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbwpjovn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtohniavok.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtorionpcf.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtwglalqzw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gtlafvjkub.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjxqxzkt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtqrwnarxg.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtrmlyobmg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtjcynnvne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtuxjpzhnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtiirvsanf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gteqenurwc.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtwsbopmcl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtltelvvqu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtuwmgnicn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gttwqrsfot.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtrikuxvnu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthowutgyu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtkyapizaq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gttvjtdrmr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtlnndfsre.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtyhspgsuo.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtkcrftvqv.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrdxpepvd.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtoluqlwhh.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtwnsnmqdw.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtnmohxnzx.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthvukhkib.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtoqhmsbzl.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtiksoigox.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtakkktwcu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtnxgicfzj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtmtcodteh.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtjyttfiiv.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtgrtuzaqh.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gthfkmwgeu.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtwyicwlxj.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtnzqtxsli.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtnbwgoaof.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtwlryxchx.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtkxwihswi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtoxlvrdiq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gttykykupb.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtbjcuwvxm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtlaahtotg.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtflictpzl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtdzcoobiz.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtqzuogqxs.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gtrfplyjbs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtqnlhfruv.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtfsravkfo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtbnpifnma.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvadovmnc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtjrkvwjro.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtsnokomgp.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtsrzjkfhq.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtybsjrdlr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtilmoodta.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpffjpxp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gtitpnjlhv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtcqwhbszw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtngwoqwgu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtrxaehtab.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtomldfdnw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtppvwnyup.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtnsfkvkqx.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtuuzaownz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtxnqopojq.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtlavsezbi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtsifpwkoy.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtgppdkubn.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtjqdqtxmm.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtlhmodhsf.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gtoptsrkhf.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtxddpepid.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtvvtwwrdx.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtmkngcwxq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtjbjmzvfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtsuyhpszj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtqqwceeps.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtgfbryzks.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtfjuiryty.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtcmtmppsi.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gttacjuhio.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtxxukfdax.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtdzznxljz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtysnmqsyc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtgeyzldaa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtuzlwuddv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtorikarnv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gteywswsjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtbeqrwjsi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gtxnsmmmfk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtfofuywnf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtitflbeok.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizllqjtg.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtamefwaus.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtvdlssihd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtteyapivq.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtyscgazci.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtaksetqye.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtxfvkrutl.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gthkwdomvr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gthextddsh.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwsutrflr.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtpklpmhmf.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkzkucsw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gttxmbbohv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtsrnpdxnf.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtjmotilld.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtfxbgnqjm.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gthrkrqueh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfbwnegxb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrzqdkzbz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtifxnntxr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtjchvstze.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtrdtjkrwi.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtuchtgtbg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtfwbzumkc.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtzwwnivdx.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtttqnnyul.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtfifnjecb.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtzgdvetek.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkikyagx.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtvihzrkkm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtrlplcfra.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhfhfbrv.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtlixxjsfm.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtpghgbnuq.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtqcwrancs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtalflgbae.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtrvwzlvkp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtilnqibzp.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gtbaddkesp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlpjqfybk.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gtldnrciku.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gttiogtjvg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gthwtmbezk.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gttaksjdlg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtjggwottf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gttmcgeoze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlnhnixp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzcmisno.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtziexxkwu.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtroeyhfvv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtoyvprxfl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtxmctmdew.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gthsvdzson.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqawfiwlf.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gteakosobc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtsqajuzha.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtjjgwlhym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtqeaepbua.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtynyqezru.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtnmnxieus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gtmlbglojv.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtkexonxhx.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtqjbgsskb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtbyhdrzgz.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtyiismtzt.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtblzeohys.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtmkocbdsq.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtyziihenu.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtyubackww.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtytitkgvp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtilkrbbjk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtftzlizen.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtxymrvebp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtosdzwqcy.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtivpkzzam.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtishjntvi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtfcijktlc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtqybtqawe.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtfjbdfigk.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtzhdlszyq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtiptcufzv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtfrszaoif.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtprjdmmkr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtauyiuebt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gttilmismz.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtzosxmjtg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtlqdtofrc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gthcmjwibp.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtcdwhyfin.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtbgkvddrg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtgpgayuep.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtbzwitmpc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gttvnpzhir.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtqnzxixoa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtxwydniqz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtwncdhnts.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtekwipuhw.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtqwqiwhdi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtjcaovwoa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gttdywcxot.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtadntznmp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtekqsvxjl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtjkdqoyhh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtjzgoowuo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtokfdqzdz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtrsadktru.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtgdthecmg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtojirhoau.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtzbuseefv.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzgxbsl.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtpkoeeqlr.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtnsmsqhei.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtfrijikub.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdykjpbju.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtfpcgpwvj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgquimzrs.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtthuozlcp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtamceobnj.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtymzhsapb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtedosvovz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtwjvflyum.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtgjgyonfl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtfboknytp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtzgcrhham.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtakrszejg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtgbreibev.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtylodxjmd.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtjjbzqfxl.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtwpetwclp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtgzcfabwt.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtmunuqgjf.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gteywjpfxr.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbyxomshb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtuteczqym.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtwuoqobha.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gttbadecej.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gthxgknpml.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtvuotfhoe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtsgxqhzjh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gthmmzcbro.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtidczyjge.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtxfycvnlk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtsyeiehfj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtmndgufnx.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gtzfybhtfa.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gthquvdzaq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtahpzpzzc.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtlwrghugc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtfuxmnosj.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtnxurlfjh.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gttfytgsty.html


<!-- 参考信息 -->