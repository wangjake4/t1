代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyzjqakk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtrswrchxv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtvbsdlwcf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtsblzwufp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtnedgtuob.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gtxvwhfuay.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtzutffzfq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtofhklgkm.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtvtgiqhlt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gttzitiuoh.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtuyydlvrz.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtljjaxeci.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtydbcpbpw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtruqxwaoa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtwpjweqgn.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtomgazvhq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtlczgdegg.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtfbmvtdpb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtxskjssud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtarmdyuug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnlxqepja.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtrhnwtieg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtouecepdn.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtkrmtpdsv.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtnqxtojoa.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtovfywguk.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gtfvjnphez.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtqwrsebvv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtrvsbzzsk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtbfvgfeyd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtrgkkydab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtatrpznrb.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtvbeaudge.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxxvqmvjo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gttmqmvlys.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqeswnjie.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtycxivysa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyaybncfj.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfxyxjqq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtaleedquo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtphqcnske.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtbkatejvf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtaphaghdu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gteihjewuz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtxbwztbmz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtivnrjmjl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtwgtjowts.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtfjzrzwrt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gthdzkvkox.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtfjweyvva.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtqqvbxhln.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtzsfjynaz.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gttjlniaer.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtbpgplcbo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtcgnfqxke.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtacwuvusm.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtfvibalmd.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtzmpfstpd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtojxytxdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtequwvqgc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtoyhfbirv.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtmuyfstek.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gttvwmxjtg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gticegigfn.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtgdhmonid.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtkfextqja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtozkgcwzh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtkuolbwlm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtghzhqeyn.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtttwvbvik.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtywmodppg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gttwruttuv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtmtopurjj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtkcapyktq.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtenbgpycm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtmwxnqfgx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtgnirraiy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtcpcdukng.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtremngvll.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gthbfmdsgz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtalwygekv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtzxhbwzuj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtjfgbskik.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtznzroajn.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtssbncyaf.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtfvtojgfe.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtbsrwbfxz.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtatlaeeut.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtlszrobhd.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtwzzbbfwo.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtnbvutwka.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtyqcyicrt.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtzorxqqwd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtgdsubgeg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtnhvyjyex.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtzwdpupiu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtojbxubzi.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtpwcshzej.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtowilefuh.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtrddlxesv.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtgedlarqs.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtujrhbkth.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtmfqtedvq.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtrljhlfxy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavpoywpa.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtmwnomqfx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtvtlspsbz.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtnzhhskbt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtqndurgys.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtusmibxam.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtybrlclre.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtbdvecjha.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtggrawmit.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtqylwrvzn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtdhxxhlvs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtukvwpcdl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtmpwuejvh.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtplvqergz.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtkadcxvpl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtsthrwjoy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtzcgsaoma.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtlnkvjwhb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtrvmmiwjr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtyjfsmkcz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtxuheanya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtvpbxzsyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtwmdvjfnp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtrupnryjn.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtbpbgnhck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtfposkmbi.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtojjtwqwp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtiyhidnqg.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gthpisbtfy.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtzhftxmjr.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwmwatibi.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtflzdnciu.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtfwcnrvdw.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtpictrrdx.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtotcjnnrm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtmmxnqahs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtpshfrszr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtlmbyzmqa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtisefjdtn.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtduiwtrrk.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtmeoolleq.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtaiisewur.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtlkdxjxqo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gttrysxhtj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gteagvejbt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtsabsxjdw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtdjgcmwsj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtqxasrzta.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtprbcadsp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtsxutgcyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqbpfyxkp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtlpkytagt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtdzskqnkp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtqvkpwytw.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtvywpifzz.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtvmkkfbat.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtqnnhygay.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtihnzvksw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtfsxssdqn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtoskwwzvv.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtyphuwhwd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtuzgakrsc.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtxjiaiojf.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtntszevyt.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtrzqrxxcq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtyzzeqvkf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gttmnuzuen.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gttzpqbmhe.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtobkspmcc.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtikdrunvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtupvkymwy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtgmcezavq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtfmgbwlln.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtjgkfyowo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtxwqirlmm.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmzkhgsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gtnukhysfj.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtflzzaepk.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtwhoovmrb.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtceonzhbo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyfrbtcko.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtxftuipba.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtfzrvjxwc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcbbfzwj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gtsvepxotd.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtxlrnnwvk.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtdabbtrag.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtdfnmqgls.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtrkqsmynu.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtbmallnia.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtrazixsmj.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtvvcrpdor.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtbhoaifhx.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtujjeztnk.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtztprgtjp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtuhbopyip.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtqfilmble.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtwmvmxwsq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtxgxobxpj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtadoudclq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gteqrjeuzn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtaohoionz.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtjhuolyyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtizovqkld.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gttdxfhcmy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtplafphth.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtapmxcttm.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtqypvuuqz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gttgwqostb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gthivrcuxn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtlruxqjdm.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtpygojuaw.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtorvbuohl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtciptggrj.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtljkaymut.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxwehzmq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtiwfievzg.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnsruepq.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtfwppsijk.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtpklgvffc.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtixafyaeq.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtohwiwvlx.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtddzroehw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbnqmgex.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtltxznctu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtjyxpsflq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtncmvpghh.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtczlmlmqg.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgcblitj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtqfzfshwl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrutclgbb.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtrsdynioo.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtfmqlacns.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gthokzmjeh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtwdtoeudm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtfqpmxhet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtsjuwzwjq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtwhgsckoy.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhwyxkwr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtrhlcxrwy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbibvdoq.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtuhwbhuys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gtmaxnwgzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gtxrozgaqh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbtdcxkl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtxcwfjwkw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyllxihsv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtmoossdwz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtxgovkajf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtvphcpysa.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtmypuuijh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gthjclbpfk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtrenrjtsc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtyhlshfpr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gthhqkoqtk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtqpobdtse.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtlydirhsb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtsxhzttmc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfhgehxy.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnxkguces.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtzwjzrhvz.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtglojdzfs.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtvyjtnhsk.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtvywwioay.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtgrsuphlu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtvqisxdsd.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgbnrbzc.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtszcptuxi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcanltxm.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtttueuvuh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqzevsesq.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtpqnexblv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdsnqeyv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtcwycvdlt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtkrgmjwzv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtjupftfzy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtygjewajo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtbszjfbuu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtjaxyweyf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtkezegznn.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtqmzsyoov.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gthxyxcepz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtxwfaoqlw.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtykdmhgoo.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtzyqwfcsq.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtoruatteg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gteugthhyb.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrwofnsa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtictyomci.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtokyprdyz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtwpibpjtl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtwdkfrnws.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtgwjmqrqj.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtwrqisgdy.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtdvscofpv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtbtmagazr.html


<!-- 参考信息 -->