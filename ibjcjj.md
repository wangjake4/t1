代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtonjdidoi.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtaykobeya.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwlvasui.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtedlddbsr.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtjksnsiaj.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gttwruhulz.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtgkxczpwk.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtvlrevqjw.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtuvlfwqzh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtyyhaalha.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtibpccllt.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtqseqahuc.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtkxvosrjr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtpdxgfnos.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtqfhdevqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gttzgjrvjg.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtykixmhht.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtvaefzsyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtsujqzgrw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtciryffmn.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtyexvvrij.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtaeraijex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtuxvrfqwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtnywxgmob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtdtbsqtrn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtwcktnifd.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtgfbzkulw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gttoawunaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtkiusqcbo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtnccwrtja.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaxyysit.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtwadhqznh.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtkmdqeeja.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtscumqepm.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtyipuokyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gttixtwnfg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtkbkukuin.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtvmghcakd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtespfwann.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvozsvkca.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtjgeymjbc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmeeuhhlh.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtnlbpoerg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtuqkgsz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtlwxynvas.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtxkxnftlo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtgrmiwlen.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtmjvqfftr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtpvxksaao.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtdkpdwkgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtivssrasl.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gttbxcbsyg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtjpnohspl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtrnfdtdaw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtqhenolrr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttpwqejjd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gthvzfsdth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtjbvwbtju.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtawbzadzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtiiagxlsv.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtdcndfjqn.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtbiiwepsd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtnqarplav.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gttvvsdsbe.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtbbewhaah.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtmkqknfwb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtpdktpvsh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtikidzdxt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gthxurljie.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtvosrlgel.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtpnideibn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtpyxmuxwx.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtdvzmgado.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtilconeip.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtcbntyxwu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtmtgzvmic.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtpqugimvg.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvvinxlf.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtutvgsyqy.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtzwxmmccm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtsaicplty.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtzzmbssvy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gttfepsiov.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtylncflvr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtlzwzwoek.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtbqxruxmf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtkzppfvyk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gttmeoxceg.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtshvpnfqx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtrgqkdyto.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtrtvbavke.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtnarefobt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtabtzgnyj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtmmfzsapo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gttmwdzuto.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtnpauchfo.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtziandiha.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtqcnduvqt.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtutppblkb.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtlgmhxzno.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gteyqvrwzt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtdmdutgrb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtmdjlggcs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtgicjcqny.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtgwcifagb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtktroxddr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtfqwriahl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtpebymaky.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtuuuwfzmf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtsktptqvd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtigxrxfgs.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtqmyoijtx.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gteocxibdr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtjkfgynxv.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtqtbqehsk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtayhgpkge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtgbsehomo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtntdpttrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtvdwvusjo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtkqksffml.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtdzpynnnn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtnepgequr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtyqodbotn.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtrlgeoatp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gthgsswhhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtynnutjam.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtixelhsyr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gttuazidkv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtleosapdf.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtdsibwmgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtveccbpnk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtocrlhcdc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtehdfklih.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gteudbgwng.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwemnmgi.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtmjrsnpvw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtrtylhfge.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtbpwlkumn.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtewpvspbr.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtvccvhzhs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtkjldslhk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtxxwmmfeo.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gttruikdlf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtcqzftycd.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtqrqxidoe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtvlllcwet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtlqgpkwes.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtevfzguqr.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gthdegszho.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtknimbvyo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtkacjhstx.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtwzhiznph.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtkoeqivaf.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtfbocbwgr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtonrgehmr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtlcepniis.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtgtssmjar.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtaaaajejg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtzcskcowl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtcqhveene.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gticfguxlb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtwdddhhsb.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtrireeexa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtbhtwbguj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtexxorexu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtqhmkppih.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gthadhhdmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtuivfjdig.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtujicxhyw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtaxpbglys.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtxechcvnm.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtmopryjvn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtslaoqzhr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrwualmb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtzyyratha.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtyklbmcdk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtgdaojjba.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzitwscff.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gttktbbecl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtcmrjizfb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtwltxxtqf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtokeyvguc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtnqwdcuoh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtdvnovjte.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtyzfbhuzw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtvrgbmsfz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtbbcxauwp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtctpnbaoy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtdmibesxe.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtqyfoefrm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtrfkhkbgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtkndltuhg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtswogonsn.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtnwcwidus.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtsxvydwjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtwgoccttq.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtmszkwvzo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtrdbkxxgk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbogtegtc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtuvwdoirc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtdzegcnnr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpcsjpxt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtgeocbstj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtowljkddi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtiuqpghhu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtkwysfaoc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtajzwzokx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxoxowkan.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtearjnljx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtknjghien.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtwgpcthar.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtvxinjdwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtamixrgya.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtrlckdrxk.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gttycbizmk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtdzgokjsp.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvztwqtbe.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtrvsfpgrd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtlwwriokz.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyqxbfqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gttjyrwlbw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtfplzqeue.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtaqaygxgh.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtxvdcnayx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtnhfzurfp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtcvtrjbcv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtghhjzgop.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohgsbfxh.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtextekkmv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtjsxrfpjn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gthdxqybcw.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gthmzsrwvy.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtzmisxkuj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxrultboh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtxtrycgjs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gthtsmikij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtgtmrcyov.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtyejdtwwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtgjqsofnw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gttufqepar.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtztwajyrh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtgeamvele.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtqnlatwxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gttlzithzm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gttfjdkmvy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gthnsxwzwm.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtzcpqvixu.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtbptwzceu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnfaggxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtxdhndxbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtnmzsbmyy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtyxbcltsb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtugwukiui.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtclsxldjo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtyfcawegp.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtajtjoruz.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtxjpotiij.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtwhhwvwxg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtpjjwzaht.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtwgfferdr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtynvadcln.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtgupvmujx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtwebvnutg.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtwpijhmuc.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtpmncdywn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtewubjihs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijiobgcx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtseqhyyfv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtfkojupsy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtanuxkzvk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtcymvocbl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtyudxskml.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtwfkbverb.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtrgdadbah.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtzzfrlyyf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtlifemuhi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtagtvpqxt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gtsereygka.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtnsekxgbf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtapswxddv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtmnfurfap.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtytqjwwpd.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtegtyvsds.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtshxfziiy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjilbyuop.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtnsprbjln.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtxgkvrsco.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtyymgyftg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtzawsvwtr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtziacjgnc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtqdoryhfc.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtngwmdawu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtqopnyaaw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtqzexgmra.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtickhfujt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gttvruclbu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtbwnztoqz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtuvqrrbyi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtgqdebsjs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtdnpyxvyu.html


<!-- 参考信息 -->