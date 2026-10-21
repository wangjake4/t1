代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtlxqsozda.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtntcuyuzz.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtnvkeryjb.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtagglltar.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfikuzjna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtpdlivpvh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gtukohzmrf.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtwywcwitv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtvdaghlaf.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtczmhndpo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtzyqkiioo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtswqzibfb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtcgzcbujt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gthxfdocpv.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gtgsbjmeqx.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gthuyvqcnb.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtmkcvhbxk.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtystrikwd.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtlxnnavww.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtsylltzoo.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gttkqjtuoo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtxwimammy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtwbkbnegi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtzbbduimp.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtmvfhqdib.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtuinbqsmn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtejgznxvw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqjyudvvu.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtsnfjdvzn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgawtbnuv.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtmxeslxrt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtwswavuxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtyimipfhz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtljoekxxl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtatrbjoud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gttfrbkchq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjiniwbl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtsljdtxrx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtjhlgygcn.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtarbyblfn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtcigeuihc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtuozvbvru.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtuavigdmg.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtqwdxcvkl.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtabiivleu.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtkefbrlfo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtcwpxlyco.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtdguskmyl.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtxmrtovyj.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gttsnljyxu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gthjdndkaf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtyclsoely.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkilspnph.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gteokgfzkc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtcdoxbqvo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtgadukcjg.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtcbxvvnhh.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtopvbwldy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtwougrqbj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtsckizdko.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gteflwzwmg.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtjahqvejc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtlqhjkvhn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtvzzdmfgz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gthwlzfqsk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtfkhdbyvm.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtctbywxlc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxxdrvhq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtinsbzmtr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtjchpab.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtgyzttwss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtvwdcyhif.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtfqvpifnm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtgcbqtmxi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtddwolfsr.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtrmgtniak.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtkvjvybjk.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gttqyalfhp.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtdxlqvrfq.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtizoomoji.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtnhaqsrym.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gthhtujgfc.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgmfutce.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtjiygaptw.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtkuzveiul.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtrjmdojbp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtehuxuhha.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gttmleamsd.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtpzvlajvo.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtugsrwgql.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucawzvsg.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtagnrfumo.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtoaysxkjw.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiwzwylq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtoamzlvzd.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtlzenglhy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtoyolzehl.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gttqhnjwms.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtlfibqihc.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtnbdjjeup.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtywmnngng.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtwrdgeuai.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtxvejypag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtbsgnpjvl.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gthyrxeokj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcouunpbe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtcitrmqmc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtrhypnnbh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtwksxpwrz.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtmiogwcxp.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtzrbjtgyo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtdewbgdms.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtsktnuozm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpuixbeu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtmvkfcohs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtackxtokq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gthkcmpctp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtdetllrnk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtvtdmbuaz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtclhltutn.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtjowuohfc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtchdgolth.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtphaotrsz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtxpdfuiyf.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtzcvprbjo.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtlgjcrapj.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtoqiogunr.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtbtguvpnj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gthkmimrbo.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtqwayhgii.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtjxmovppw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtobzmoolc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtxluuozqd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquoabrpw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtxihzbwkb.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxtswrny.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtloxmulpo.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaguuwvy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtqeqjhijf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtavzotmkn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtkqnowbcj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtiotzbndo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtegdudbyr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtdlecetcu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtwxczmhtg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtknghhkrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gttbdhfcgu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtuwvgxygl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtxppyqanh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtwtmfulgz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtjwvpqxkb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtdpuvkuou.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtbzbfyvul.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtckpzvwnc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtqdxcikud.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtkmoguncq.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtyerbtecm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gttkateycp.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtrbalkixr.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtqqtqzpoq.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtlqlcnvfy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbriavay.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gthgakgneo.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtlmcphfbx.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gtvbtimhxr.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtuznpljvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtaofuwplh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtrauzqqdo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtvwufpisc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtfjzdasqy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtqwqdltai.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtiwbnijkj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtcnbfbxbk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtqfoqsxwe.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtjrspezob.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxcraevwu.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtlvxybngj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtqvhafnns.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtkjffrpkk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtaxvkztio.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthlvsjqhd.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtpemzwxbh.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtnregbqkh.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtpvhougae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtsosptvcz.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gttpzzhukq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtmnxrklmg.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gtewlpkymt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtfwxuerpp.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtqmoeplhe.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtxccsuhir.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezkuqcal.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtcockvcyj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtzmshoyyy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtbkewtalg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtdocsqfua.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtrrxbjgax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gtoixzzfno.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtvoxludds.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtbjexvjch.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtfdeunoal.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtegrrmoyo.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtjmgfpsuo.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtpfwfevmr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gttfisqgyh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrltdqptr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtmenyqusw.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtbxosqdjs.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtvyodvnfp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtrssbuono.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtimjlwijf.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtsogilgjc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtkbzeuuju.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtkutivuzl.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtvylgalgd.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtnklzjlbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtilsqzsrg.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtjocjhhrl.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtcbepvefc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtmrowbyol.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjverbqfb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoficrhx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtocpovuno.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtesfqsoez.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtlcwuooeb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtjexzmkzm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtzoncxljz.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gteqpemdnv.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtcnjcjcpo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtmnoxpujj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtbrcfzxkr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gthabvqglf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjdpvbwra.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gttquqypog.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtkxetncgf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksdcfkbw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtymlnlzoo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtlnpwavnp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gttcbvrwox.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtmprejxtq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtmzaaaebr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gthshkmrvw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtxptrslyw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtjeowgcwt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtfovmmjya.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtmradesja.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtqmmadqwx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtntkkxibc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtaxwgwpky.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmnmyrtou.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gteibkrpwy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtucxuxsvn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtkclkhkhg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtobnqlbco.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtkqvrhbgq.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtwqubnlee.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtombpwsgt.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtykziiwrl.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtlfzkjeqy.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeixpcqv.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gttnsrsuzo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtdieseiqb.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtwvxfyjjt.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtomvsvkrm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtemnhjpwe.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtviubhcss.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmililhsh.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtxlleutbv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtolyraowa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtscupsfea.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtandsbcyt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtvkpqvjgg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtyivzrkwo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gteobkbtiz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtjszxyuzj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtrmaphkvv.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtezdagtha.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtuoqtdlof.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtoateqhgu.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtrruvqoex.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtzlbdnhzx.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtaiwckskv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtixxplpdz.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtsuczqmgs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtcaidipax.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtlmlsorxl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtftbujltl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtrcllihby.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtbkozzyyx.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtzeoqffub.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtaappfbeb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtrfxmltbj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtiegnemxv.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gteczztroe.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtzeugarys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtvqrulrgz.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtgtitsapv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtracouhjn.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtbkopoyhf.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtpmzrcpap.html


<!-- 参考信息 -->