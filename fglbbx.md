代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mflporuk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2wyosgxvv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2sjtinisg.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2mmmwvbxm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gt2fqlngutx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2bipozccg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctqzpkt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2qzsruahv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnykhdq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gt2mdonyppl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2ciysgvko.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcwecwbp.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2oezheqoj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ortmqvpl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2iauvjjrf.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2aspfwwch.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2wrbnxgeu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2rncxwkcz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2vntudlgs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2rlbmqwhm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2uwtdbqml.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2szidggox.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2adxykwwg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2omykscar.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2tpellrsi.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2cdohljir.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2gtrwzqlx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2gbwoaipz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsxxsxdk.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gt2wpdxrgnk.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gt2vbdtqxjw.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2fenmkkjm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpuysqva.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2frmwjxzz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2nasnfzfm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2vrpwpcjm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2hxumhwqj.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gt2shkphnrp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2qpwlyisg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2etmrgynl.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2inusynkn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2hjlgjyan.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2zpaoenxe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2fcdxssun.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2xeodppcy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2gaivvmkt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2oasdjaeo.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2youhqnej.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsnmdriv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2rgrwczsx.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2kbmvjvwa.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2ztmsuetc.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2nsdpkejw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzlrkmyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2bfijsnyh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gt2zndrcamr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2lizwwcgs.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gt2mjyuyzmc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2dxafxsyn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gt2kubslbih.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gt2ywabqhss.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2wqzwppsf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2hbjvovzy.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2eomnaakk.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gt2rgzweqsn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2ybvxrmty.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2tvkqdfns.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2hkklhyge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2dgsdfumz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gt2pcxvjuqw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2bgsznodm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2spzcqrfb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2ymglbiqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnmhdgqk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2acssmbza.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gt2rcvdqtzz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2xlhclson.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2afwexzni.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2ekreoupc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2hdtwdcpa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2dnalabrr.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gt2glpsrbds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2iuxlrsxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ihcwstyv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmcpxmlq.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2ibaxohej.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zywguhel.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2oyfodxug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2iiyxmkub.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2luyjyeww.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2ndlkfbzg.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvnmjdrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lajuhafv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gt2ocfgbnti.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2bdvefzix.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2gonhljbd.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2insvcdla.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2awkqjjsn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2vpoqnxhq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gt2sbzwbwhh.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2chkqrrai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2qcuzgwpz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2yduxntlp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzderocq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2kdydvcpj.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gt2vcxnnubh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2mkmzbycu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2uyhjsbyc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwikjvob.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkqagulx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2lfweemqg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2ljdohxlv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2xehuyxyq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dopbuwcv.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gt2jtjxbmmj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2dbcsqebj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2vykvktee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2evkktfzg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2outzwsit.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2vdzhsdiu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2exiyitjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2ftgtnusr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2oiqwczyi.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2ftgpwbdb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eicujiqk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gt2aorpnken.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2vjxbkgde.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2buwvtyji.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2zsmyokgw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2derpbqes.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2djcrwqvx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2hrmytuit.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2igmnqyzm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2awldgupb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2hmzmyxnx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2mwcmguuk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwozegmh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2cahexjwq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gt2phrnyekj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2itoequoz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2bmkhtspn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvyhchtl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2ylgayggh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2nasbdtpb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2qhflhyib.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2mecsqpsv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2rzqgimae.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2wybzrale.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2stpxqedu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2udqrdkdy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2qijegtfs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gt2yxwwhxxx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2uovtpfzc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgbfyjcx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxdvhvuq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2xmqzpxfv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2uefvggug.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gt2jhnplwwl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2nmofwpvb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2atwgnfen.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2yxmfomti.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2tlzmbcis.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2qhzbmyye.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2ldldeevh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2szxpvnxg.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2vhkfcfiq.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2rtsdnvae.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gt2jteiggdl.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2acewiygr.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2qgynoexw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2tsxyhegd.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2jegghfli.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2phsyqqvt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2waibtaiv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2hjoztuel.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igqcthga.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2vagwyxta.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2ldqdkbyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2ebxixbvf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2jimghjfx.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2kzkgtvvj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2bfdfxugq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2axkqujoh.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2hcnnimff.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2lfwzpuzr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2tepgrzvr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2lezlpifo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2bisrvnsx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2xrgjwamo.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2jvkwhaql.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gt2aejpicqq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gt2ezrvhbcu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2zeprlafo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2nmrvdwul.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2aczriavu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xycazmib.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlyridbj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2pqimeltx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gt2oithwjfh.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2ztmmsgav.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2tcwuxqtf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzwjypvz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2ladluthu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2ohomgszm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2nkotmhcg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngekhzbr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2fqgrvumv.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2vutdqelk.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2hlfmlpzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2pmlffnvk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2ftuojeyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gt2qlxbsoii.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2quuvaqwh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkimewci.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2plwlvauy.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gt2klvaatuy.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2gxkiwjvv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohyncezn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gt2llzdtbqg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugpqkcoa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2jflnawoy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfnugawg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2kmdvoquu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2nrstdalh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2dnmausqr.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2jcrzihsj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2bttdbykz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwpybemb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gt2hwfndkgx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2qfmwcqli.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2ebyybcrf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gt2simogsef.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2ykdyfbql.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2yrgmedhb.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2anpxbahi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2uzienyah.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gt2rjimmsws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2zjlpgazt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2fbsxijhr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2fmqhjzna.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2impsgmya.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gt2fflhgeph.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2iacorxjj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2fawjnrad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gqcuhgfd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kepmuzms.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2juonmrah.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbjthrxh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vwzuwbrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2xqikzmaz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2qtxhslrw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2seaaqjey.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srissssk.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gt2bffnhssw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zmoqvdwa.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2kmlfxzfh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frrijnyn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2txtyjsuy.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2tpnjzlaz.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2nveldlqb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gt2ljfgyjki.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mlywdgsw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2waubnabx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2qouxgsvd.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhqhkhug.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2zepkbzcy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2czjltlpt.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mzqcggma.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qslbcaap.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2wmbywhxh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2vlfwygii.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2yptnkcks.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2wywgncid.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2xvxllobl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2rsivlgaq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2hngdzdcr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2kmqgowct.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2mbupspdm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nqtpkskx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2nkpijkoo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2wgimlfeh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2cenvwwmt.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2gavmjbpt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2xsqodeij.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2vfnjfuwf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2urxpzzwk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2ojcylcqj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2cmvsnpoi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2wnhlidrt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2vdfzjrbf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2xikmurov.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2dpqiuctz.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2jrjzjzjw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gt2jscsihsh.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2kjfysdfg.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2bigtztha.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfmxmuql.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2cwbayqzc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2vzrmypsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2usuvfmff.html


<!-- 参考信息 -->