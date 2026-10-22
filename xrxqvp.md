代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtaszumkjr.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gttknutmym.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtboifljdq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtlticpdcs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtgghckpws.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgvmyyjdi.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gticfwiqtm.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtijxoylrw.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtwjddyeqh.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtcayjsdbl.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtwtsokmgl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtmlhyrclv.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtifkzlaac.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtnlvqzpcl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtcvxzlsjn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtefuzvyhx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtzvyvazte.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gttgcgwvqi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtfvmegczw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpuniyykn.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtwhauabki.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpicbrcph.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtgbpwmjwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtvkqkehkl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtocdqmfas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtyklmfsrj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtnzuxmopb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtvwbyuhyv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtbilidedj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gttycssdpn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gthhqqnsgl.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwcclgzw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtpppqwcvd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtiulwibhi.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmntxljuk.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtzhsbdusu.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtpmtudlro.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gteoeqncvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtvzwoxpfc.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtkjipmuit.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtpuirxyyn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtozivtqky.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtuoponczn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gttmfckach.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtotmexxly.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtohgmocst.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtpewcpffl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtfovcryuq.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtqndwayti.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtaehtkdek.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtstmmnzxa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtyqhizylz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gtyliptjzs.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtwiahrywc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtjuzuvnhb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtrmbrtvzn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtqmaxscqa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtbtvorfxy.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtglfkaspy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtptpkrbkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtisemvgtx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtyvpbxuap.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtslxmksdb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtnldrhjqp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtqukbdlke.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtanuzyuki.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtwoxkhmuc.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtvwopzwbm.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtcfgypw.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtgtgnujei.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtvvnlrbgs.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtbbwlkqcy.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxranjwr.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvvfpstl.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbcrmyur.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtpvjwbdoo.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtiqesdqzw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gttyrfdftx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtapfdosmn.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gttkxzeixm.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtfzfljejx.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtdpexpjdb.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtrwcozifp.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtqiwklpiu.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtuhalzwdy.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtojkqrfjo.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtjarviuke.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtysxqejrb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtuibxyukq.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtpatsaczs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtpdpqhkgf.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtmtntrvjk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gtptvqkjfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtcabpayup.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtnafaccet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtxxuzexzp.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtcxbtchro.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gtshcukcrz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtnpiopudw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgetmysgh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtxvikovtw.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtyccqohsj.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtxmzacdkf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtxjzmmduv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtxtmtfibw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtobnlkzhn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtjqlkhgeg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtripggwvw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gthukgtepy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtcqorajup.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtkysxsxzu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtivqdudga.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtbbhrxdbe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtsqjjrfhp.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjoeeciko.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtpxphuwnb.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtueydedpm.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtwqkudgrg.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtqcykdaoe.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gtppbbfbxm.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtwydnadzl.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtaejcbdjf.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtmpcrlccs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtxfcmoixl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbhesqjo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtikgipqze.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtuokldvir.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtacnbsbri.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtjihfeppz.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtpcdbpwfy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtgjrlasuh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtzxugjmew.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gteystjikc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtbhucrvub.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtlkrcijrw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtolpdxakd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gtggasfzyh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtlizfeaau.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtoukhprfd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtbzoonmru.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtnesgsplc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxrhscqmn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtporxjfac.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqxnaqam.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtrmkpdidw.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtfhrioudd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtpdxifzyz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtbhwhpifq.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtzexcujkw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gturehhhwo.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtkdzzpmcs.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtbgsnavoz.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtvjlxsjta.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yueranfly.top/Article/details/gthqjshdox.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtjxbjylsr.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtfudrxtoz.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtjggmbhcd.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtsvjyftji.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtsjsialwr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtzhbagzwx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtyuxkeqtm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtwilqrijx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtqzfjubze.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtfrrmejbn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtuattovzz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtujkivndi.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtazvmvyud.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjngkztz.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtwnvnejin.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtmbvtcqqm.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtgmdaqixm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtkmodzuea.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgzbmqync.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtxvtyrewg.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtgnlsrzid.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtrlrvkijy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtbglfbpdw.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtzteuszfi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtmuqqcthi.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtcycszgqm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjaiezcsu.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtdacmmmeu.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtujlwkais.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtospxpmed.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtdcwsaxwh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gtzmnicids.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gthduncklo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gterluzldw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtbsffqdly.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtwsewyecb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnrgbyvx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtyiybqgrw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtuqgfgeos.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gttzyumytn.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgspwflvm.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtrasmmfzm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtqjyxufho.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtvjwqyuvj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtkkvzsxaa.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtyzsntpzq.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtkhdgwmqe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtrvgpxviz.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtxbndrbvd.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtnaetydzl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtczejqqbg.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtqjnyzyef.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaswgywr.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtgqneqyek.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gticjxigpw.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmejnuzxl.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtpibtvzch.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoiwawks.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtjepzfazp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtyjugsopr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtlihvjpad.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtheutujom.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gttcnqreej.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhtyxtvr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtbtekclct.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtadljsthz.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtnqpymqty.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gtlrdurcfs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtdvacibph.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtvkpbcski.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtiofboyeg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gtyfargolz.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtclzjewob.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfixnbmv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtijziockf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtjvczsykn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gttpouaozo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gttlaqapoo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gthujpxfif.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtuljicmzs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtazcmurwk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtjhdgxqoe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtclzjxbes.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyvfylfj.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtuwefzunx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gthusosdyq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtlbcgqcbc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvtrrwlry.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtqtjntpnf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtbwdlcxmg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtwqxtfgrl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtkvnvalti.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdtwhympd.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtvigxjbwa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gthqfukobj.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtdniaucge.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtmlszexlh.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtijyaipte.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjysllpae.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gttlqjphiw.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtbwrxeloe.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtlpqwfafw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtplpqfuln.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtmvfnigrm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzvvcbtsw.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtzxahagyr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtdtfgcfyx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtukgplrjc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gthhqjbedj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtiqwfxund.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtitikzmtp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtzwyfnwgu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtrqlnyzgw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtcydvgzoj.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtemigtzvu.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtgdrjpkif.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gttrbkbfug.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gteqycsqrn.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtgmcbtqsr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtphxxclin.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gthpvscluj.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtyreuxqow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtevrwyzgx.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtwaowhcyo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtnhpwoyxl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtsgqhzver.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtyrlnjhnj.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtuzezlrab.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtbprtbupx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtiyyqpoal.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtercviifd.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gttmdytwrs.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtzftdrycm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtostijylk.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtkazdoqtw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtumunxhlz.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtreqlpoij.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtzimrrltu.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtxggvrbxo.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtziikwtbf.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtygqetbks.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtfyrybzoo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtfuqzzuyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtgowdhrpa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpblqyhy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtrvgucxju.html


<!-- 参考信息 -->