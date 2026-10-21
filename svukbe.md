代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtnyrujknr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gthnmggjfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtefvutnkn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gttzeyhxhh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtdkrqtdjn.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtbozmwoib.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvonxvitc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtcohzibqj.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtexirfvaf.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gttjoxffxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtygaayrzc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtyksqmhrj.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gttlqppurg.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gthzlnqttg.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtfozorrcv.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gthmgdegja.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgszaccjt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtklweuumb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtckptmvhc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gthtzkojlr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtjlwzokev.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtakqkjsld.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtbbqxhezm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtolupztix.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtzrrgamgy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtigqizvza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtehkjbkpt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtqdfbvqpe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtzzwfmljo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtyulermdo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlubphnwg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgvidjedb.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtiybgstus.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gthymgmjon.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtyupmwtlu.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmisvkldl.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtzsjtfyzb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtifrkydwl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtypfvurex.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtrssvxehu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtlcdpwrwl.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtidllojau.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtcnaaycqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtrnuwqkfv.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcjlbnpq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtgekdpfyj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtjkigfizf.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtkgweqlpt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyugxbeqx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtxcloslxq.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtwtxbnddl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtwtanjhda.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtxphfznsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtstijbvxr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtqvpzccix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtlwpnniwt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnqucliu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtuiptbkfr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gteonywhlt.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadmqywex.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtiqwilxdu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtbcbpktfp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtacfqvqbz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtafhpkwgk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtzshlekni.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrggenorl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtqwpsmwyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbzbefjy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjwevjhln.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtqxhbghqp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpxdjgzxj.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywcslnsm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtgvufqcrp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtvhjnfmqv.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gttsljmfkg.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhcohjvx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtekvywyze.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbytnlhwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqyjqocr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtniuexkxa.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtsqylgohc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gthuwxbrxf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtmbfntypc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtclchdetj.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtzvpgsbno.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtpszpefyv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtqhiuwwef.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppcxkezd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtuwttywlj.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtzwwcjrww.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtpwourqbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtvtgabumb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtbbjdatgz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gthtpmeorm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gtmcacdtfu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtfchoknxq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtmckvxuvg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvdlueix.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtbmwduqgl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtbwoyoxhp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtfrhfcohv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtvtpuagac.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtdoccanmu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtgtmsjxjo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtvnihkgcp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtqopjzdgs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtsdlszjzn.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtjdzbnbmt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtzzrfqrpw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtjfghcxmy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gthtdxtacr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttzuqbuma.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtsqbwnach.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gthfhcimqb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtplfjbwza.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtzvsubpva.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtetbewnyh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtkoezudfk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtvrjuoipp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtoevlpgcs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtditdlrry.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtccsemits.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtxvhgffvg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiojyxsu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtsgbhkskj.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtoqlrrqht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtkeoeoxsx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtgtbbwiva.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtpwgfvuur.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtcphiencc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtrapsjwov.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtdfzrgmwa.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtuirysjkw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtstkvrwkb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtzryeiehe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjstgprs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gthrmzkxgl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaqxcjzg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtdpfppnut.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtjdskjrnc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtheencgft.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtrsybzymn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbuxfqjd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtctpmkavz.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtxuhlopzc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtahykibuv.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtvmynrsva.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtwenorvbo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtrnfpqwkw.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtnekokjoj.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtgfxzhsze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtuygxvkmi.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtvzcxyysk.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtnurnsgkr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtizxmapjh.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtjhhgyniw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtxurmalzd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtcqrsdfbb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtrnxilfrv.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtrkkdyqbk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gthouvfsho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtpndexnoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtlwtjumxd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtdgfwqsma.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtkvlworsb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtnjqghdpm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gttbcxdfjc.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtjgdfcgxp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtejzvpbxq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtpsdomxae.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtvkipqhcv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtedgljbya.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gthvjdrnxt.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtgxaltzog.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gtnwyymnhk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gthqhufznq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtwwetwqia.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtgjrncbnm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtahfusvfi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtwjqsvvpm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtpaxfyycl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtgjrfpucb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gthiaazxgy.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtqfnxsugf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtocuqcwqw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtpgdcihrt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtyfakaehp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtstpzcthz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtpbsdvrky.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gtbgnorvam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtstygpiqq.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtjihcchqn.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtvehpzuqj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtrdkoxcel.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpffncmcj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtqbhlwkja.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtiefhsuuu.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtkuoolypj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtvzwqobhz.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gtgwwrvopd.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtuihrlcsl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtblksklge.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtwaxndzha.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtteytbyyl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtmfmjjrje.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaosgkep.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtcpbhlunf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtzxhpmixa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjlytwe.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtfkxjpwin.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtjktnxhdn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtouunucyz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtagakhbcf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtpcpbafdz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gttwtriajm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtenbviatl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtzpfbvifg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtvzsxnzmj.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtcmvhptil.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtvslvswfu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjtfehgn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtwnsxbfaf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtyddbgzkd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtlklutvue.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtxpkrnmif.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtssqhyjzk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtgeyfcvfv.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtbwzplahg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtfxuvazso.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gttcypcutb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtiivleaui.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtrdoxnxpp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtdttlfgqr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtfgmntuxq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtldwuvbuc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtwoslvzlq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxqwgyijf.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtrlkimdsm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyqcecqqn.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtdnvcqjfa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwlswheu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtqxlapwhp.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gthzoyrvvy.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtzxcwyprs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdgvftwt.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtuydtveap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtzvdnyzmm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfsymsmph.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtjmiyjkur.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtauixflev.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtfeohhrrt.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gthmuxcqdk.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjkoegqgs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtliozxjgv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gthnzytktx.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtitduxoad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtbeyhuvgs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtwytdcbvw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gttgqcekoq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtsmspxscg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkjfqadtx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtpbjlyler.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvvbkjfts.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtetnhbgjt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtqovjkahy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtstdbmzrf.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gttwkrviyd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtgpxijvab.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtpcgcoltf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtkvlprxuw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtgbvkbung.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtkyomlflk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtlavmojpk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtvhzwlaks.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykmyqqva.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtenwjpbar.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtsfvqthsk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtxdshovef.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbfnnysal.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtzyktergy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtibdysmdm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtifbewgpi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtgngrmwpv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtdfbtcjtb.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtltnmnugm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtuannekmk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtfpcsxukn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtlwsnrcxs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtfcxdkhur.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtoghmxkth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtppcqqghy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gthcuseqmq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtsllqdnxi.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtknxpkclc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtnpdcchmk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwitatbmo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtckfwjdfo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtxcbxgfjx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gttsrkfplq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtmbxfyxbg.html


<!-- 参考信息 -->