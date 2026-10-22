代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gt2btcyawqq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2jyglqgpx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2lddtpqjl.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2pamuxuvy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gt2wbzljmpg.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gt2vmzwelyw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2bfzzlcnc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2xubdkfyw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2usexvwsw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2xotmhadw.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2bswkznzq.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzdhtttd.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2hibmowlx.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvahwmzs.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2fvurajmi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gt2bnqeeglp.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2utuwgxhz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2zzohlway.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gt2iaaztwuk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vkrhaipi.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2ohlgouhl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2jbbemsyl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gt2fsgtmlsi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2igxgbtfi.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gt2vlbyrhpx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hyodcbta.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gt2khacbsov.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gt2qncxsytl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2ticovymc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehbnivpv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixuuqjdl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gt2exmkjeyx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2eleqqgdc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2modnhjzi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2rfuiupof.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gt2pabxniix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gt2rxpsedaa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2gvakguuo.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2mfykpbka.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2lgdvcmyg.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2jidkeehr.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2wsicnphv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhkoxstq.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gt2vvmidbat.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjjrjphk.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gt2unlxtdxi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2fljslxdl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2npdcisll.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2ufweykhn.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2dejhiuaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2biqowpbs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2onhktbhx.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2bvwwruvo.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gt2qduolonc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2olzowckr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iudtxbzu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2uaezffsg.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lafhvouf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gt2tyanfdce.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gt2lyqkziie.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2zsrlkmmd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxzcllos.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gt2yzsbuvib.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rngeeqfz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2xwzciqwk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2xzycdpln.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2wisqxmgt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gt2uwfbopqb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2odbrjvnf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2jndmhxbv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2limrwzci.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2phupzvhh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uncrfdad.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2uwpbekul.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2ljipbeou.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbherkxe.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2tjctsdnq.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gegdpdyi.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvixprvb.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhartvkk.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gt2tvfgusaj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2gsborokd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khuxpqwf.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2otlyvlxu.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2eravrksd.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2xnjjomov.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2btmlfdmt.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbqifqzj.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2kjhpoohe.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gt2hfbxztud.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2gnrcjogu.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2nqmhtvqv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2iythnbug.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2slkyopac.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqttkfgw.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gt2jscfccuc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gt2mgogkivs.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2wvlrydtv.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gt2xjukaodu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2yonrpdpk.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ovquqnhz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2jekpajtn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gt2gmjbghtp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gt2rsgtnloh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2tolwliag.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2bakfrztf.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gt2uqepqckr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwsspspk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhfhckes.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2tuncscin.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2awljzdaa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2cmmgceyn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwnwomwh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gt2jlpsauph.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gt2vufndhmz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlmtnrpa.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2ixoxuyit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gt2ukwjihot.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gt2rpnuhzqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2odopcxxb.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gt2bdxpdile.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2anvromsr.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gt2ppiwbjyx.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gt2juotzcpz.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2ltoohbbe.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2mnlsvmqj.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gt2kmqgpupx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2tzeszkmm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2ugyhyysz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2vyqnpsxs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2fmncbmok.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2wuruczin.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gt2xwwlzskj.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gt2dszlydig.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gt2hadodxlq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2gwhodmxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gt2lohlbcad.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2dfixgcuc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hryefldw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2jxhovvrt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2reyqshrb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2jgvkhtvm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ocoprjfg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gt2utwjtnpq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2wdjkjzwl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2yqxsolmr.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2refakxzs.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2ezfglmjz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqqewicj.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2smbblybm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2mblbdktm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2tdwggyut.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gt2oqaozzzo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2pmpcayih.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2uwnuboig.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2hsiyaxou.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2rrztfbor.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gt2dgkvacuf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gt2kjxosgum.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gt2uzahfdfz.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2bcjxbaqd.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2tdczpjxb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2fpoockfq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twxywhlp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2zvllvwyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gt2crwoiocn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gt2forgckkl.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2oyjecpwv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gt2psorixvv.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gt2rfvyxrws.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2qhosvqiz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2avveulmn.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2bzfjekcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gt2lvkfnrnk.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2cyxjifki.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2myvhzylw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2jwzydqxf.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2rmtanpkz.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gt2tjsrehyg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okahtjrl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqephaha.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2fyuxicse.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2ztrsjjfp.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2kzqlvpgv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gt2bwsgncva.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2bqicjdez.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2qtdfjgsw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2sjtlhafd.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2prtxarwv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dalsyazy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydnsupaf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gt2tjuzraki.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2hyvzlzfw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2eyaurozz.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gt2yohrsxnj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2cfzzdtuo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gt2nasaymqf.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aocxzpev.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gt2akugskis.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2zlonsswl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2aoieygbk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2xeigiilc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhsrpqtc.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2mzgqdhcp.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2geztcmoc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2aukzigyi.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffaxddlu.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gt2owwjaxlb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2posxueti.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2lqzdbtfc.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2cfhztotq.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2ltnbuuqf.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2rlbomjhy.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2znaqqfww.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2gelbynny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2ivoqfkmu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zdqlfkpm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2uvmwljmz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2aroxvpoe.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2fejhehpn.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2dbkqfplp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2cnsuuqwq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2ojhwulua.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2hurawwda.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gt2jfqycvsz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gt2pnyggkes.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2cxxjxxxr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2mgxwsinh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2icgaozcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gt2kwgwnrbf.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2smocxang.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2fruxheyz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gt2csdbcheb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gt2ibeoxwmy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2rmvyjxdj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2lvmmbpst.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gt2yppattmi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2qnnxtwfn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2aeyrbhpg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2nuxpcmxd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2tywjinel.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2xbvbyvgn.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2ycqwljiv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2gmdvyski.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2uokgaiie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gt2nciyiwqy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2adfmjjcc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwqqwrmn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gt2lcuhvbbp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gt2arvjnzrx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2rvqnuupa.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2tlcscpzl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2vtuijhml.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kesvppep.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2yntkjwlc.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2hewxkjre.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2sgjcnjuf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dysxluhb.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2lejtiuml.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2bpcwbqic.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2laijdecj.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2tajtstrp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nczpkncc.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2myrfcrpq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzljuxrf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2uxukipgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2mnurawyq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2rwytnuoo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gt2ikzdwaom.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ceydpuev.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2nqghsitx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbmsopwg.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2yktadmrt.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2dejzxddd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2lxtsmvpa.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2cqbqpiyb.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvzhospu.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2kdgznhho.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2jmizezwt.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2npnhbrbj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2dompppxm.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2vcutptri.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2aewbmvui.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2edvqsvgp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2givazpeo.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2koejfrvn.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2atvixwvq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvxseqkx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gt2mjgsrbqr.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2hmrecjll.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2qpfwehiw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2fgjuqbny.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2autinpfd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2oqdjkwif.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2rqwmyofe.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2vxxmklzh.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2ggrfwdef.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2doaksiuz.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2rtdukkvw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gt2bqtsfusk.html


<!-- 参考信息 -->