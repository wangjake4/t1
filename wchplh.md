代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtufjwtgtk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gthvvqnntb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtwdkvqyaj.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtjuqvfhwh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtfjfbewzf.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtodmhsljw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gteeslnghc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtdfbdgucm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtptajlxtq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtjtlxfxxx.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaupwtdd.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtimcahnka.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtgwwutbwz.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtxwvuhsnr.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtbmjgqvjk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtyxhgxrth.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtggyxxdhx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gttaqstfgj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gtpcmfshak.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrkpxxrze.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtqdigpeuz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtriljmaeb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkgayimv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiuyxlzmb.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtuttebjgm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtccmwnbey.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtpdndmzvt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtsezbjmjc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtchqqkwoq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gttqktaavq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtutvtcjch.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtlsphtedj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtqgrjykes.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtjcwaucnb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtmorobqas.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtuusryurg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gthuqqnfwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtdmyxxfsz.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtvkhqkdmg.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtjekadgyk.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtpwqrhgli.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtlayvlaax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtoueervkr.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtsyxmcpwi.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtwhllcmii.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbudsnofk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gtezvnbdoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtsflfludl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtfqnpgaki.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtitcvzzej.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtkkvfffpt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdomghkyb.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtcwyahhwx.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhtmidfj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtcyegtaut.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtnzvnxygv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtyroozuhe.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtsaohpxue.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtdjxzsxyx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtumeilqcn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gttcwcrlbi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gteljtypvz.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtnedwyswi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtyzjbeejb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtvxhpaknw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtspuqloxx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtkcospxva.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtnsmskypt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtyxtpengb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtnyppjiml.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtkckhlvjh.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtgxavxaiu.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpyqsvqu.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtysktelad.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtbhgdkwys.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtddyqcnuq.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtxetmegfj.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtoibvvvnk.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtzyjtbmrk.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gthgxnyllu.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtftlpfwfs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtxysqwayy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtblqhpase.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtwxtiocsd.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtajhjfgof.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtyxvxrfgr.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtkudeywhk.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtkzdtzqpl.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtjrevtxyu.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtnzaxckbs.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtkoxbecwy.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtuldxosex.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlemsxcsq.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtaekfotyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtqplosnit.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtzrlsuyzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtqxpqbtwq.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtacidujgc.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gttrujamxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gthmprwnta.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtktiptdey.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gthctusdvj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtyvwdkxit.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtqqtizqtr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtiveyxvvo.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtqrbqrygg.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtzvjhdwxg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtnbizsapi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gtikihjddf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngiweqdg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtylibkwry.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gttucgflwj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtkfdpetbf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtzitgnddx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtraanxozi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtluubhkld.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtlnqtjdal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtpmlskxny.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtqjpvijnc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtsskfknab.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtnbuzwdum.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gteosfrzth.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtnqspgldp.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtyxuitogj.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gttwuvsrdy.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtoqptffbt.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcklovnd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtkiywjxca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsfecewy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthhwcdkm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtoyqokhny.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtqstkjpcm.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtersjvzns.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtwwijgwuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtppborwam.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtbudlpzdo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtdcpenbpy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtwvbighva.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtytwghivm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtqnbesdkl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtoliafstn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozzorudk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtrlifkouq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtktqsvrhw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtkukrbjtp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtncvkbbgk.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtoqmcwxke.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtnnajdrga.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtwlppdznj.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtuongszhm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtryxrwxcb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtwrsiqpcn.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gthcdeafks.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtepxaaqxo.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtsfkpjigz.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtlackkpky.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtzvozigtw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtdpqoncpl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqodidoh.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtyybgqnkr.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtlctvkawn.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gttoetfdxt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlspweiwt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtnllgkbvr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtsrqsbmld.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtzzehexmx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtjipqgtjj.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtjocczafw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxnjbbse.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtgdwgfnlf.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtcbopvveb.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlbtlpbyp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtjipfyieb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtlveeoger.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtdbkqwrsm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtdpsxmbgn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtduahtcjk.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtrxvewbzk.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtzbyotkuu.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvjorrcb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtjedmizwt.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gteeshmdwo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtwscrkcjh.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtzicrvziz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtnybvbogm.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtyqgdupdg.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoybxskfw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtceticfpz.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gtmrohjhhg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtygzizuda.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtmuttfjjz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtwrzuuhex.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtwmnjkhqx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gttdeqiucu.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtbkhmtlbk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gthlvqdsdv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtpzlpacnj.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gttcrcwdlr.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtzxzeloxn.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtqkwzogzq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtygdqodvh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtrqbdwiqy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtybyfzwnw.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtjgkdeidu.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtjlvcjuhb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtjzzaugxt.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtbvxfgkie.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtpewcvggx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtsrsgkmry.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtpugodehx.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtsutdjugx.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtufaujbzx.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gthowrbcwf.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtrjayyzyc.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvrjgveuj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gttkwpcjkd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtjlratxkw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtzcrenqla.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtaabzahkp.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtenqpqkna.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtfksoquii.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtfkcjvlwm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtzaaeyvlp.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtzvgqvlin.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtkggbtfmh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtgwqvfziz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtyeccfqap.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtaecdzrrf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtvhrlkwrc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvmxrsno.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtawrmkfez.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gthowvnpad.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtwyxbmffq.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtwgwlxisv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtdgzolngr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gtuleaxgck.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtqgzbreuj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gttnuaemqp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtmdtvihgb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtexgzkthn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gthzarugaq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtmbwpvpad.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtxxueelia.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtmoosobpz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gtyfiucnol.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtpzlvzlmi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gtgsglyiok.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtpyojszri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtwupkipbi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtdmsgcarl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtwokfiyrw.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtkqidgedv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtmmbmrlwg.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtcykanmrj.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbpppttvh.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtpizoslmd.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtntrtwvqu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtrqdcodnv.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtotkthbhp.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtrrrlunhz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtedzywzgr.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtieobdftx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttmthhjcq.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmfbygtuc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtlvortseu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniuxxxvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtqwzholvd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtowgqesqz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gtfkvttsgd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtgjxyltsf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbndyzxu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gteqaoqapp.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gttumxwnbn.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtxhrpszhu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtysysipyb.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtjdlhdgfl.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtontzciqr.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtezfdwcpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtzjcawhea.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtjzxryngn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtiddipncu.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtrdvqgbzx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtedeonref.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtzqabugxv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtgkmdkhul.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtgprtkigl.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtwrogpcgs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtamvtajlx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtydwkghup.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtoabcymmr.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gthnvvzaic.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gttgumvxaw.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtsjlayspt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtowpvkzam.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtmlkjkvqk.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtnuwldurn.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtyakiaruo.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtytmmckln.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtbnafekcy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtyqpaacxh.html


<!-- 参考信息 -->