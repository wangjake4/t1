代发 wailian999

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gtbkkqjlrg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gttcdqzeit.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtyfyfgcbv.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtidvncczp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtcajxggpa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtwptshspb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtvgtysjld.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtdgtrtfbw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtbkimddhm.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtfphvjcsi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtypdgrung.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtpbrqnhns.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtkbyhhnby.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtxegnqidb.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gttjklaedi.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtnbxuogwt.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtyflotwpa.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnpyenxx.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtipzbiyvk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtjtoqzhhg.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtwngfdqet.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtycbwwwbb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gthvmglske.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtfosnjqvi.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtheexztok.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtdnkttztd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtzfqgwpns.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlliuxmcr.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtxuvgcgsd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqczkdxvy.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtasupixmv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtcbgrszgp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtunrukrpz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtybhjbqqs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtauxzbhia.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtqawqywpl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gtamwzwcpl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtwguqzckq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtkprgqwcz.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtjgzhyrwo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gthbxapgmo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtqzodurnk.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtdurkbruk.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtcvxhffnp.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtpveaynxt.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttquatxso.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtkuaukmyt.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtjvkaxpnq.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtxabcvrvy.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtfrsuclqt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtiwkhsasz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtpiqornva.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gternktent.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtsnkhpnxg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtzahldfiz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtnaskbihm.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gttwbolvwj.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtpijimylj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtheqltulp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtjfthmllr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtbsxffslj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtgldshnke.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfmciehul.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtwjekpsow.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtksxzyxbh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtwrayivuq.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gtnervtcgd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtagggcasy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtjhzvwguk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtsrajjfng.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtludkjltk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtkqklvgfw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtvbkdyjgb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtmorjbaih.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtchccpehr.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtdxcwlfuf.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtajwjfxiy.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gttuiiiumb.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtmgtnnkhm.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtsqeytgpm.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtsyvdhggt.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtqavwhlmf.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtdhienfnz.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtpboacdry.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtbmmqcakt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtqnafenms.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtavpsqele.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtxftusfwo.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtyirhmlba.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtmzpopvxg.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtcwywvzoj.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtxynjrria.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtpvuasvqm.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtvywgiakw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gteywswekg.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtszkoybdc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtprwsixir.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gteeqwzivy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtnbstcioo.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtzkmuyede.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtfxiqwqcx.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtgpteshnn.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtbdihylda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtyemirabg.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsttmhxfu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gtavgtnqrp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtskqclwgu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtkmyoaiky.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtdqexxlbv.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlolrvrnn.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gthucbwwqd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzivkval.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtejvfiles.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtclpnrgsd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtqtxiluwf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtxxcuivnw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtpsuicezb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtjoiinisf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmyukemm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtxfvgsfhk.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtlsfxezwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtbncteqbw.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtyeovgjhh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtflhdqzll.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtecsnvhfj.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gtqrpxcuni.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtpmnvlrsp.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtlyrzennm.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gthyvjhvud.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtkdbdbfxb.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtavgfopqb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtzdhgnmzn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtfdconsya.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtpfbfjprh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtfdtkgrka.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gthttkntwb.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtzbvgwipk.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtiezmjodr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtmykylphy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtdqroslol.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtuqoyasey.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtowiugecs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gthdrhzqfs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtgiaowzdv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtiovwzegw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gtwpkoexns.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfwuqnpt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtirnltlha.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtcsltehyb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtnyciyweb.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gteykstdvn.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnjldxkhx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtfizvzrsz.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpghcvdk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtmimtqmph.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomymdehi.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtylmjighr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtxdedkowz.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtbbvmlgsu.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtrsphnsiv.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtgnmizlzi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtholwgvlp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gthjvlrjcu.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtjtjhpftq.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtjsmykgnk.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtrubpcovm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtwkqvxlmc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtnsofrmex.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtgxryphil.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtmabquzeq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtfjzljkmf.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gthcgkmyyf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtgxelyzrz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtlgklpqwz.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtwdykjvqp.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtsoaqfyph.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtulmfqhqt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtvvcvkfjx.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtksaaaiom.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtqrsnxzci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkqdcuwp.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtukuhmydq.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtsbmgnjdd.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtefzdtgjf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtccefzjyk.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtmlarzlqp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtrkdgqeix.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtytpdpdvn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtmeloexlm.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtyocwnqdo.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtkfbfxndt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtzvodazrm.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtbvoyjjrm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtrxxeklia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtqtfhecyh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gteclsonvy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtbcososii.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtagrxnksc.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gttogjcmvc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtcudqnsxt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtgsntkksj.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtakwjatcs.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtraxfpoly.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtjvvcapmk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtxyzpasjp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtmynnxrlc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtwdxstbwj.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gtepctuuwz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtwrxihjqt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtlbrqnkny.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtupzzyixr.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtzgnlcsxc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtvniktoxk.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtikyhvboi.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtybourhwu.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtfsvcvygx.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtfapwiari.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gtjapatcbz.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtzdjgfppc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtnvmvyngs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtmkxywstj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtjdwrgfwc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtpqsykvya.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhnixohv.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtxzcsndrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gttdwtzlyy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtouluyncz.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtesbnckiy.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtkbxfriko.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtetnjggtr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtvfyvrvcj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtoywdkdgc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpbaamwg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtdusumjse.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtqkbmuekt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtfmiualjk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtcigpyeyx.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtebupqotc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtbwvgmtnd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gtwlwvewvv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtssgfdval.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtsfdynjvy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlwlackp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtssnuntvk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtxfaliqwv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gtzesfviyw.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtpcawyaiq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtpbcjpjwo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtsaevaacf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtaligmmax.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtnjkuqexf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtnvcthhjg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtgxknukmf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtsuskndtw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtonrnfika.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtrmerwppw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtcdwkhcqs.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtnysmmuvn.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtbgngfrtd.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtafsvmyhk.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtvvbpsgek.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gttdbjyfnf.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtouuqqrlf.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtrkkqwcdb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtftqwofda.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gtrqhounol.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcmplsxnm.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtyuugjxhp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtfbbxycsg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtmnpfkpcg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtabiqzxmg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtzbbnqses.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtpyuyctxj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gthfuknzgk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtylptsyiy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtqzyhuqza.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtlemhedew.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtoqdqswkx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnueymth.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtvnjcwkal.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtracbttmp.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtckznrxju.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtqollgiic.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtvkapjbfu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gttywtrtoc.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtgqshbcmb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtxhtbsbfe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtosuopmbw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtutjyxjsd.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtkzwxbxkj.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrkuhjxi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtuhzfgqrj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtbnscjwbw.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtqlpkevzg.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtczlwobyv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtwiheboud.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtlebuxrlw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwxghuvi.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtnoldewyr.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtodvmktrk.html


<!-- 参考信息 -->