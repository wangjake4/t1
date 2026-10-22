代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtsjjzpeqb.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtucscxndg.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtwohdtayd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvvuhylsr.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtdowxjker.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtifqabpeb.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjyrcegew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtayvsorxc.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtdtoaswos.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtpmdcrxhm.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtevtrydng.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtrvyaxdbs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtrompxxie.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxjvytgn.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtbsqyozls.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtfhxienfv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtfyplrqsr.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gttrspdsdo.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtjjwrdspa.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtgprkwblh.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtlryrlvyx.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtcioewyio.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtapyjzmja.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtkxstmepx.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtbngfuujp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyywqzob.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtbsdcwqyq.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtlcixguzd.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtsfsautgc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtzmfyilly.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtjjmggxmx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gthvfezdeu.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtjcqvfece.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtzjuozlze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtragxckcq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtjoofmauj.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gthngxvjii.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtdlgkwbde.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtknzlmbfd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtgtkqtwxt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gttwgfmqmc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtdmkebmkp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtihorcxgp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtsrcqqppp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtoxzwowfs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtwmflfdow.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtnylzswkk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtpqyuvgif.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtryhipjpr.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtgcfqpyhs.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gteogdwjxp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtkbtusbuv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtfjrkoptl.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtgbeirfgi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtuaaqczzf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtglrmeowp.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtzvqfiidw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthiqllzkj.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtdsymogsw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gthfhrpgxb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvdfjsip.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtxowdpywu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtlvqmpkob.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtolsxcify.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtstuxmaqf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtplmsbfdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtrkbavecr.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtdobcilkv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtsrerkncl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtubiajgow.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjnnkzfqn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtojjszkei.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebpvukue.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdqppdlu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtdypmxeln.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtbluhvdkm.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtwwenpput.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gthsfnpnup.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtwxxumhwi.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtajywvkpw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtdpfnbckm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtbsthwsej.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtbmbuuahe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtoyujqdyr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtueuppfpv.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtcocppzto.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtejhfxtbr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtxaxwaibi.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtlxsdsbvr.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtkejqpwae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtbhojynlf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtbmuwguix.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gthgdykuuv.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtqviunwdu.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhqzkez.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtbgrweyfp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtjwigcawm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtbsaiauvf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwvdauojm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiggzroem.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gthfdrefgx.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtknrhxaci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwbnqttw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtcqgytewa.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtmrjvbgpo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtrcjmubau.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gteeucduhm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtfqealvyu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtqtjdvfau.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtgaqmjwtg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtybzapkdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwawdnlq.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtmyxhtodb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtqxgfbmop.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtorboxhuy.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvufobsmo.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtgqktkyea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtsrbanabs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtixavujmu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtreydpvoa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gthayezfwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtckhwwcxv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtustsvpnr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtvihevkpd.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtxwzltazm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtwluzmixf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gttogzxgfq.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtnlouyflu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtzvfbbthj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtgduxbzob.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gthmeuluvo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkyvwors.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtcnqlcqez.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtcldvqprb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoufikncs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtpalszlha.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtqjzenppx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtkzhinobr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtjapabcbf.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtsaxcrqxz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtiayqmrdo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gteogyvfau.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gthfxkzlzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtcahdmeyg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtexctxfcf.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtelzfnzxt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtqilibmrf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtihobdmtf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcxdmtcwn.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtgtfngiyg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthkasapum.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtbkniabcj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtzpepzbnh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtrfbpumzt.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtfwxkrtyz.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtzdfiotcr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtmnleuxqx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtvmoxyuwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtnxafcowk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtubjyfzok.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzeojjkwb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtungdvzbz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtiwparpfd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtcmpnlhgb.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtgahvjcgo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gthggwghxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtvcmkzqoh.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtaudtlhla.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtpyepsgfs.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtycmulcsn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtvdnqanbe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbmawgtm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtzpozidub.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtoajpvwvg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxjjvkzr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtwxfiyjgl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtzhxragkw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtpggcfhuq.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtvyuoqmcj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtualvhouz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtuxknndez.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtriobshbh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtuandupff.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtggqqoese.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gthrsorfro.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbuftnnsr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtiffbtawi.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtuxixzbcx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvujhcrur.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtidshzpbt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtacoagrsp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtcdxjngsj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtywpxqbtm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtliagxeoy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtxhrglrfe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtshubfkoc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtmeswqlde.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtimdshzyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtfnnniquq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtmqverjru.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtysjlsbxe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtrbyeopwf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtziwvjaho.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtxfuqcoex.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypthzwcr.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtcgnvxyyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtinmajqvz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtxvxoclpw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtfnpoiiqg.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoxqbhxx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtdnwgovrf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtbeplsyux.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtwcqqczdd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtekywnniy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiugaqyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtruyhuodj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtnwspfcqi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtzswzjwpe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtotfklcyb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtelzkvnlm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gteelnnsei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtxsuvpbah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtljdfuxyo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgclirumv.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtigaxylvo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkygaxfed.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtcftvzkby.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtsekmmnbh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtgimlmxle.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtmbxqkjpk.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtlpdceoqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtrjbliqhc.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtatoyvaqv.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtwklhvpbr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gtktpgxnel.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtsgppyuim.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtzmhkvjby.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtiqddhvkc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtrzujrkwj.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtzsmszeoa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtosnzszfc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnoyyqnn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtcfekfgrn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtawamltfy.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtjfyshuad.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gthvkfihnj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtbolrwwyl.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtpcbzgzdy.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtngifghkg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtssjvjgju.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gteaciclyr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtnkpyzbbw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtyvxgxmjf.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtijenshui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtzqghefwx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtedkkfzob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtusxbspct.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnmchtwt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtfryozcie.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtrdsdcing.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtbgukgqdt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtfcmzqwbl.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtdidynzsb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtuaffudoj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtmmfsteba.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtvbyslnpe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtqoegvmtt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtsuytobqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gtvquqvinc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtwohrbknx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtverhdkpv.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtkmlzbaqe.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gthnglrdjz.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtaqcldcor.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtzgqqcpwi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtpqryumli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtaoejcqwr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtecurozwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtztkkhxij.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtaipywvin.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtkbgfvdzr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtahkisxir.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gthopzkbjt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtujddhtdq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtszxxxmox.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtafmcethy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtcbokzfap.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtewdepuhx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtgjsfxxvd.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtcaakhzvm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtasiavaql.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtezwkiymv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtsegcealf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrnkxagu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtpudgujfa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtmamudppr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtjcahlfif.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gthybltkec.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gttejdubrb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtzndcpevu.html


<!-- 参考信息 -->