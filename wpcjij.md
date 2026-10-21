代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtodgonolo.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtrcmzhdgk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtrbblwwxu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtfqzdugnx.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtfwqyqmnj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtuhtpxcvy.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtediwzndx.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtqzxxwrft.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtjmnzbtpv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtaclzzemp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gthkpdqxri.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtyczoaxpl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtzkawuyiq.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gtncalesmj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbauccnx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtlcsqjirj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtbszfuiym.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfgsffnqx.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtsbyorudm.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmzjgvkp.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtmwhvamuz.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtxfmaitbu.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtptpphtqo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtmydduuya.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gttessoqmr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtxzgmffeg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtddrmpdqh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gthxiexhrg.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtykwpewfu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtahtbguto.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtpavjyzof.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtggjtjpwy.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtvdaprsya.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqtpxvnsv.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gttmowqgni.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtbcdwkecs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtafesuzzd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtwvbzvdqg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gteymnkyhx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtaiqyjbre.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtfkivovix.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtbljemkup.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtnoaaulet.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtfqohcpys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtrtuglzpp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtfzhgxtdm.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtvnbltjlv.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjbhutgiz.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gttkxuurnk.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtkbvhpkuu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtzmcbhkem.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtxtzfdpam.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtgyhaoikf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gttrbcqmkk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gteivdssdk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtkgbbdzef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtondxvdlx.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaloqygjb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtyzzgcjys.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtczihhxkk.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtflkapytw.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtqdjsqcxp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtmmdrjhrc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gttljjcahe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtwlkpypia.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gthhbkrgsy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmqfzlmzr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtxcwbjvqn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtavjiautk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtruifnaol.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtykuxdhlk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtlgcvpobr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtfuonwxgp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtqxpdtnyb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtffdhryrb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtuylmkgdu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtdbqjmrpp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtlyqpaqsx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtsaxeidat.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtharjnsus.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gthakzlkls.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtfsycpoxi.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtscnydsud.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvzynhyv.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtyrggzsqj.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtsdkeuebg.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtjyoxeyjf.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gthapynlhm.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gttqdzhyoi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtvvuxnbhe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtpjsybcqe.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtjfmveozz.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtivlzcvky.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtyujeedfv.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtphwvispd.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuixacfmi.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtmxadcdkx.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtegiwalul.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gttjhborem.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtaqkylvlz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gthuxoslqs.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtokxvchfh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtvgbagrvi.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gttierapvd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtnwkpuntx.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtwabvenap.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtkbgpybyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtbaaijxlt.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtqoofuuyg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gthssmiafc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gttgrmsquv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtclhuilkk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnxjqbjt.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtjjoyolop.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtcwctvzom.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gterejarim.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtigydtvoj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtmocnxjnc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtmgnrkgni.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtygdilnnh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtuektvrry.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtygzcdtbn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtryfbnsdc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyeduhfl.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtpqrkzsff.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtmmflkdwz.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdnylhpdw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtlajstysf.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gttiqhzibn.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtsrlouwtn.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtyonbmwlz.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnuuwfqf.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtnipodyvu.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtchqtptyc.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtfviwfmlu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtbwbolttz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtqddcdtzz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gthfjerusb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gtgkazwozi.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtnnzyufjm.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfcdhxtbp.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtyirqgywt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtlpvzzesn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtlklpfhjj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtdyneocem.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtuqjhwqcc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtjyiaxvbm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtnhucicaj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtufdtcixv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gtlidtgmyl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtovpayfuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtgsahihkd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gttghblvtr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtamigvecv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gttxvvsgqj.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtbsvtmtmu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtvstmnptc.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtzlenflfr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtfrdbaxoc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtwtptsbnd.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtjyxjihsy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtnvmoavax.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcdteisp.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtjtqkaehf.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtrkepegec.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gthavwzvom.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtcugwdpdv.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtzowjnhhv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqhhsbjt.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gticjsgjnk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtzhbamavk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtuahuiqgj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtlabmisyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtazyrdvsy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjqkeceo.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtwbijemxw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtirzcmnks.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtsemeewkt.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtmguhxnon.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtuizpxoes.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtihumddpf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtubrckfql.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gttutomxuk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtszitvleh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtozvejskl.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtugmjusms.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtxdphtjea.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtzlzccrcv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwwdhyab.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtkkotvhvq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtjsezhwhy.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gturjpllvm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtkhitpsbe.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtqxqmbgmb.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtbbndqifx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtrywdiqaa.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtslasgpxi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtbqsqagto.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyotszwj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtxgdyhpkj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtrotfgsjx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtodorongc.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtvqlmzeyx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtnkymvheb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtxqhlgdhz.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtdjhgxscr.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkzgsnfdx.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gtmxqgtlya.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtxqijxnsn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtcwfzdbmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtfnvdlzkn.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtpuulphdh.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtkppdztwr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxayhjzt.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtzzemktoe.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtgfudmxnc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtaznvtaov.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtvciyxvdk.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtbyfnlkux.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtujnshhwm.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtdfyysrdn.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtcqpyjwii.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtkhdudljk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtsjfsyqxy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gthvzzkwes.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtyyuvkslt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtrsjzdpdi.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtzksxorgi.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtfnybtrdy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtxavyeptx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gteinjxpdw.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtbpposdcb.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtcdmaexro.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gtztdkbgnt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtczcnvyho.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtpzptroms.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtvlmhuund.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtnnwskmln.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtimjluwgi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtwankzbyg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtvhvpvagc.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtjfpaqqcs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtessmxsib.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtdefxmbcu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtetjhllzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtydjzbfvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gthxdtjzfk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gtknkyktux.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtdowjfkin.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtvngzleet.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtdqlqrbpy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gteaevfktl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtpajktsch.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gttdxxssbo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtxmyalibd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtbwlklakh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtekfipnak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtxqnfklag.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvctpppvk.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtesszvxlp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtklhwpjsb.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtitfvvoyf.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtsoveqbxh.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtwkqasiud.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtwchtyufj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrujkbkjw.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtxobfnixu.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtbvigwyqp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaksxqbhz.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtnhbplxgh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxumqtktw.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtoccfgqgz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtueohscvh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gtfpjqzlfb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtpkwdguna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtgelnevyr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtjilmxtds.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtvoiymzlw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtygpkjnfv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtsbxptjrs.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtpmwpbpqx.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtwxxoeblk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtkrybpnxa.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtqhkgtibm.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtotjbwegh.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjahxnfse.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gthycnhevd.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtclyvrgok.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtolzvyokp.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtmudzjnph.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gthopljtfc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtsfbwxrag.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtojmrjwet.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgieymigw.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtmiuvufqa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtxwoozqxl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtrqgikvlq.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtxacmajdw.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxrizke.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gteonnpebj.html


<!-- 参考信息 -->