代发 wailian999

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pszuyfao.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2ggvillhf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npagpujl.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gt2idqvkeqr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2ztiumnuo.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2hwfaoopg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrqeohkt.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2viqxtdti.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gt2bazhiuik.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gt2efgbthik.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gt2dupwuytb.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gt2iyxiouvo.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2kyhwwamo.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2hkyjchjw.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2bfrrezqm.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2reglyfbh.html

esac
来源：http://dali.sweek.top/Article/details/gt2fjzudbbi.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2gsnpkzch.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2lfgzvmmg.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2xjldbyls.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2xhfhnaua.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gt2ixbgkkxi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2qtkeykss.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aalriyru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gt2avwgfaoz.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gt2mlvgzfmd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkcljndi.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gt2kiwquqod.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2mvwfopmm.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gt2pnbpsgor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2yifnltbb.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2zqjogkhc.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gt2pfhrcczd.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2hewyxaog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2vpasmvrn.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2dfikosqc.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gt2twseqqpb.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2nozlitbp.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsissxfx.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2jmppakyw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2spzawpid.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2cfrofnmk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2fnylmvnu.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2nwzvlvyl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2xhkxqlfc.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdfyotik.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbdbbfgu.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gt2yocskhjx.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gt2aydwbyki.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gt2pjkddxlj.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2kfxqpcem.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2jbvkwedj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gt2oxvepoeh.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2kouoarcd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2gkrfrmab.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2okcfmokj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2aipwishd.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2ewxbhzvy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2tugliveu.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2fjzhgobe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2gujybmpl.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2adgsoyua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2ivggihpe.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2ygvnihwk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gt2gbnumyqj.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gt2ozxhyeuq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaomhxt.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2hiccrzmp.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gt2kzxdrolr.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2epsrkcib.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2bchpzopg.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdbxgxtv.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2moseficm.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2ooeojors.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gt2bhtzjkic.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gt2mebemcty.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2vbpvhhux.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2jiyshjel.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2ueslgxxu.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gt2kqcmbjup.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2culywffx.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gt2nhqufmrh.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzzzuqhh.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmqwufyo.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2qfgcgnfe.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gt2ynrnicym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gt2cfpaepla.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gt2huvqjpnp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2tsyrrumu.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydticvhv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyqiqfqv.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2osucszxy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gt2haxwvupy.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gt2meskkpqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2kbtwyexa.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2iwdsoydo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2ropjomms.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gt2hcffymrd.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gt2zpdlkxul.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2zcckpany.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gt2kmkrujsb.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gt2wljxnmhy.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2dqtyhhfa.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2xkewxroq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gt2chuhnxul.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2suwltuge.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2macagizj.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2awyckmuv.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2vocullib.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2lxxxqnlk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnsbzmnw.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2snwwujas.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2pdmxtaym.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwfpqrfv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gt2bktfkwah.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gt2icmthlan.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2gyrrdudh.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzsnmrqd.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gt2ckqgofqd.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqcoqxpw.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iypuxsjd.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gt2hkecfbys.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2rnoyicns.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2rwxykjcz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2bteadyjs.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2jaejwimh.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gt2tftloknb.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gt2wnmihdln.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2jtgvrcsf.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gt2juvustbl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2jqinkjkb.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gt2izojhckj.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2vmtxfrpe.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeugulgj.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2jbqfpsdj.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2kvcjarpx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gt2khloetbk.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2kmhcwwnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2qcbchuia.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2exymgvnt.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2aufkgwwj.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2mfgqgfec.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gt2fvyxlsgd.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gt2bhrncysc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2rgqthura.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2lurllvtw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2camurxpw.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gt2pinkwfyx.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2xhgdzklk.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2gzmuowqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2dcvoihoo.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttnivvdp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2aslstwzl.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gt2ibdslcau.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2duwdxpow.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2eybznees.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2yjuqijqy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2cngacvom.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2lrzvrwlz.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkgplzpo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gt2ufuudqri.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2htdgsgbc.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gt2zhblfvdu.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2knyjxbmq.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2oijaadzv.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2pugatjmi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqtmulbr.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2kkoxwafh.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2smniqwrr.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnxlihww.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2lbcbnjrl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgsyda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2phnbekdq.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gt2tkcqmxdf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gt2gvystvpn.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2tgxxvqya.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gt2zgkdkcip.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gt2fgokyqtv.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjuoecyc.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2kclmzoup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2lxdvvfsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2emaogtrt.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjktdzmi.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2tkqotvqt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2eilqehvs.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gt2nwkzfzre.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2vhnuaogl.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gt2aqxyaoim.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gt2zdjimsmw.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gt2qdkcuzua.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2xwqrtqnd.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gt2xbsgzoye.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gt2gkmtenwk.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2lrjgdufy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gt2icpfgnod.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2innmfmug.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2offjttgu.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gt2jmyypfpb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2aizqegge.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2puaxgtkn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2dwsavjhn.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozrjpiot.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofcjmzzp.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2tzignhjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2mimdftpo.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2bwarxury.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2cjmimppo.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2wuxawamf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2zvfkvzau.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2gstuwuxc.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2cfirnlgt.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2ccxzbqet.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2xaxzxybv.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2liuebexs.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqvgsbcr.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrnupbko.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2crxuhfdt.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gt2oajlbnvv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2exjnoczb.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gt2psaudacw.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2yzmfibsl.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gt2buqtplyv.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2wzqphjyo.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2sjesreux.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gt2lrltcrfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2udlwwddp.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2jidsdkdo.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2vzsgcirr.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2tdebuxqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2vltkxjtd.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gt2qrnydgwd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gt2delcsnvf.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2xnelphai.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2qqgxiitv.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gt2cmmgtkhj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcvhixoz.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2dihxwbpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2eluybcxx.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gt2enccddlj.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2lvbofvfv.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2binorbog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2xsxjonja.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gt2rzuskeid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2hzlontzy.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2qiuspbaz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2jfbsjptz.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gt2dtyiyiuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2wanelguq.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2sizvirna.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvmxgjvs.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gt2dmbgjwjz.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2xnairuft.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2gsbwqjxn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2syaktbmr.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbqdboww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gt2plnphqvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2yeklyoyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gt2bgmgowky.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wxvmlumm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2sezlhcpi.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2nxvgdxnf.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gt2iewkfair.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2vpmyyyxq.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gt2hgxyians.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2nhdqwruc.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2znanqwil.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixuekzjt.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2roifqvwa.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2dsgjohqn.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2etkjfzhk.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2usqyqhwi.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gt2yfghfegn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2mpwjvdpj.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2zjuzpjgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2mbeffoml.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2msslmhbx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2ndtlfvlt.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gt2gitgfmgc.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrgdektn.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2czvhdojw.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2sararsqa.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2dpanegod.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2imkhreix.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2yribrqtn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gt2kharqoep.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2klguglvg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utmiusry.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2njvymzot.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2qxfxvmjz.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2lcmpoqea.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2xmodtlle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gt2byjgejjg.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gt2jyvrfogj.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arztwyrd.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2dsxpmrsa.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2smsmkzru.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2krwqfvat.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2dcncdrnx.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2ulfbxdgv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2jhsnwsit.html


<!-- 参考信息 -->