代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2qooafacu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2chydgdra.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2vqnvxkng.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2begayuev.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbebylhp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2wtnvupit.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2pwvmkuhg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2zxzqxkyu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2nqxhbprg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2bcrlukym.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2nryptvwn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2uoyxnyep.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfheqxfy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2huzhylpc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2jhkztwnu.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2kdbvjupr.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2jehijqrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2eujcsezg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gt2apfvhtbz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2ibcizwnp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2isaouwym.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2ezenxfpu.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2hloncymj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2qnvwzten.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2fniasqgc.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbroaqxz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2zujwfvcs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2kazjvovf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gt2mfxrjwdd.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2fkthfndy.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2tlitaotw.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2skwkvxxz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gt2fziinsgw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qetilnia.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkwowapb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2txbcyptb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2yzxbqqvv.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2nfmsffuj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gt2pmhvfeis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2nopclnhr.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2ipylislt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2hgsdkkel.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2hlkaedpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2jvcwddua.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2nbanzxaa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gt2gvkybfhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gt2stxzcbde.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2svbeyrxc.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2tjoewvfp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2lsswcpev.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaijnnfb.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2uzzgzfwy.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2qnycaecd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2kbxlrnyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzwjhifj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2txvusovt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2viuxfmlf.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwzsqoth.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2jojqgtnl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2ndyaahpp.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gt2xwvxmwik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2hcuxfeyf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gt2pgrcdoaw.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gt2pkzyjqnu.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gt2twkitpnq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2abzefcve.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gt2shypmifj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2qpsaslpn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2jsogpdtv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2khfxpsvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2hkunfqfw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2zrxthove.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gt2hsbwxjmr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2hjtcplcb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2jmiwtuey.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2fwmseqbx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2cvmuwknx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2qyhmvtsv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnegjzos.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2liriruox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bszbemjl.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2pwoocbrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gt2wmptrbau.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2clmfazyp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cyjghskf.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2bmnublco.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ioxxafhn.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzrpbmtq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2btdxswpt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcrpndg.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2bnitmfbl.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvfydglv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gt2hcdmukqc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2qqpfqnct.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2pnworqgx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2opmdadgv.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2zedeakiv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2aujeatsr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2veiqytah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2dhtgetau.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2jjfemqgg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2otkliijc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2tfbhczbm.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2zmujeowg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gt2dakobzdx.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gt2ekculxnm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2vbtcakhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2wwpvltlb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2vptikrzo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2jiiqqpke.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2xnkypcry.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2kjlmaeyv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2geyeybmc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gt2odbrmayh.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2hvdwzltw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2wrmulkfc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2aqzjewak.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2lfkspcmx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2acpgxcem.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2djkfndli.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2bylvnybk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2ghouxvks.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2akayphhi.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2wsqvhbxw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2wjpnauam.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gt2jriydfae.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2tzdlmvdb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2darqmdim.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gt2qbzuhfge.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2vholfwzr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2gypiifuz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2sikrtclj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2xkbaulrn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2umpdsaec.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gt2npmxfccy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2plzzbfvi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2hgjvalxs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2yjtkohdo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gt2lixrgrqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2llagytef.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2vdgvrwvv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2nvbazylk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbjxcwbj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2guvhldst.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2fyvsmsde.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gt2qohwehuh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gt2rjknepfm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gt2tyaderxo.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2yalbvman.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2mqtjgnfp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjqwksgg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2cpthldpe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2gsrqsywo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2uctyhckr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2jiomteha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2mqkkhfsm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2vkcjqeto.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2ikuzwnzy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2vaavcfin.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmvaupkm.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gt2vunzkypq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pecovadl.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2tidmzavf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2xghxvwor.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2vkulpftv.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2mpqlyuqr.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2tkwifmes.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwwxfvvj.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2zxvzuwms.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2newiglvm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2bnvxxolf.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2ffqkulzj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2dflsctgn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2fxhesgxs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2kvtoxejf.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2qraiockd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gt2brcrtdrt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2mvqnjclx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffxawyed.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2zagzshlg.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdapmxke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2yocqkwwu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gt2zzeokfer.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2wlbaylyn.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2mnnzoivr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2hvybmgsi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyrtgjg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2mhiowomj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2jyvveonf.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2yrigfcnf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2trbbarbe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2sikhbwrw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2vfrwvzsn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2mtyrkyjv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2fbhutomj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2llqnoksv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2qllasbew.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2pyyesave.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2brncyotz.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gt2holozowd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkgyzlkn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2vwmavtkh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2tpihvoqu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2piisnxjq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2quxqjwel.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2cbitmkqt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2ukekeojm.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2rtcafdgb.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2zjbibbjk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2hrabhiqn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2pkiactvf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgwnjevm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2dpjqbovo.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxsjfgk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2ukgdewtv.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2amtmaspg.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faxzavwl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjsubcob.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2ibuamfdw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2bkchdepo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2jtcfidee.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2wuunuvls.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2ntulfygx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2duwoxyrs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2elugdvuz.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fozztror.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2dzyatypp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnfoxgfu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2jfyhgvkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2rrujooug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ribhsafj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2xsfnxfkr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2edjwripr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2ghzipfwg.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gt2przqvpcj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2gerxhbwt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vapzqhcz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2umiqqwrp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2eehwmufk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2utpqawtj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2fvdcvjjh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2yrihxini.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gt2johwwmrd.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2ijmrlylb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2wuvjphxp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2bfsiwpfk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2jlfwgcsp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2mapcwbpd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2xdsbacee.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2intzevsc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvkwegsq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2cxvdappw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lupnqmuu.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gt2vnzyucye.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kyqvsjrm.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnobjoog.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2vvekcztp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhvsyqdj.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2msrltdam.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kanruwlb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2loinvtyl.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2cdwqmxib.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gt2hshghupl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2fhehkcvt.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2stlyxciq.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gt2ggaqlysu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2cjfspqhx.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2ovpyzjxj.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2mphtehca.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2txxerawu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2atvgovpr.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2iyxitvtu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2jbetdhrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gt2flpzfzpm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2becafqae.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2wicpidhq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2vfpuveoq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2mevxxirm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2cgldddzi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2xkvlwobd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2relyprya.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2fklkahns.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2gfjggijo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2wygleivb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gt2pdczdkmd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fgbuwebe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2urhqjcaj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2qgstwzmw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2ubwmjmec.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2nnazynfe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2drjjjhso.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2zodukvcb.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2fllmvupu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2sjybrrdl.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sguhyndn.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2jbifvmlt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2meclfcxq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2samtaeng.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2lzraohvk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2umixjxje.html


<!-- 参考信息 -->