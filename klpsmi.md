代发 wailian999

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcokjqft.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjjeriss.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2clnrhdqv.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2kjrocluu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhzndozj.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2rujrhcrm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2lcxueich.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2sxtmwlou.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2wnsartrg.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gt2xsvloenj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gt2nntfyvci.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gt2bzarspgp.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gt2litrjhsl.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2ajbopign.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2nxdkpsvq.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gt2hsoayorl.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqmgpfya.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2qtyylutx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ikvofsbv.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2bmjihyqr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2upjtzvre.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gt2xjpamppl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2glhbgoqb.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2aggsaqru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2pjfkshds.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2szjnhpmz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2chyjegdz.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fisnayzw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2ivsxoirc.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gt2banyovzl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gt2bchumzfw.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2mrpkuyvq.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2bldpyhoa.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcwtkzet.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gt2azegbivz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkgbktf.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2ojkgoxhx.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2jdkkixxm.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2sthmcuhj.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2cjoqhesi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gt2dybgcnho.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eigrldsf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlrmszqx.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2iffpxxlt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gt2wkgbxkmf.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2peulhkpk.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2rvnhqhli.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2rfuyjado.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gt2vpkkwbec.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2ygzjoebj.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2gznquigo.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2qxbwlauk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gt2peqtjkin.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2jnxcmdan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2wykyrovf.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2rfikowyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gt2xmibaezi.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovdoskqa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2afcqriji.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gt2xdfretis.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gt2lpwqyoya.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gt2azktuhxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2rncyseqw.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2azzlmrjk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2ojbptkgh.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gt2kswpwwla.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2uuasqfwd.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gt2plgwkwfx.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fsfcaqin.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvuqsufb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2xpgdhhef.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2azgvyhla.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gt2qpuoccac.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2xwapxndu.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gt2ytpnoofq.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gt2dvnbvsww.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2aicwavtx.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gt2duqkojab.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2aasimmvg.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gt2rwxkpmbk.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2wixmlcgi.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2ufmutgdi.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2vrrnaalj.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2ddmflklg.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gt2lfxcausk.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2iefmjikb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gt2xivqhdsc.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2ocpfwman.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2twcjvqmo.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2hrmznnhr.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2rsgslokd.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2phhkvaff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2abssizru.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gt2yzivlmjz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxjmguaf.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2vsikcyha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auldjare.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2roftwkhw.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2asbrlvab.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2cnvtavsw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2buybxxfl.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2vpvyefkk.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2ztjgsecz.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2uugvahvo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gt2tgmexzyo.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqmtnsfg.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2ktqiyyzk.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2ogkmtulx.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gt2dddxykmx.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jnpjeipv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gt2tnxofcay.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2rzdmkrjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvdqjayx.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2qkkgykxa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2cddanigc.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aabnoqcs.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gt2azchfxsd.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2lebcktzq.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2itnzbrdc.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gt2mtjgxuoi.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2jzdkiirl.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gt2huxkkxhs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqofjics.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2juhsjcsw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gt2vwleaeju.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gt2hqdjcetp.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2kslapgve.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2hwdakuoz.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2iiablxfv.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gt2heqrrzsd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2wwzevrgp.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2chhpkncu.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqlcupfa.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euqotcyj.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gt2ovabapil.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2uspmtzlu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlmpitjn.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gt2cmwvgppl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2uyzqxirp.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gt2zkdjijag.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gt2mfrlhnxq.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gt2vldzvdww.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2plgwuzxn.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2tsxrljul.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2zaceuzio.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gt2biwhgfwo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytzffyxg.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gt2vovfnhmz.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyjkeyvb.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2cppadzoj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gt2hkofgigq.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2jelyikbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2ykhveamt.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2wytgakki.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gt2xjxoakab.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hhvbwafm.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gt2plomocqh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ryujshyg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hromboix.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdvxlnjl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xinkujox.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2yiymiokv.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxrwenpi.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gt2lnocfdxv.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiedxwqv.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gt2ejcqxhzr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2mimhtfpv.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2uxywikty.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gt2osutpntl.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2mslsguky.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2wecstxrn.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2yzgujwro.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gt2euekpgcw.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2wyvdakyi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2cnzxklof.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gt2upemansk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2odyasjij.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gt2nbxcxwib.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gt2gdoufngj.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2pllrrzam.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gt2ltzhqxqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2bjvwziun.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2qihtiium.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2vxrgewvs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jayurilv.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2ecszttyt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gt2etgsujfz.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2xhbyqudx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2sdtlkgvn.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2ngdhyrgr.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gt2bybrwtso.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2azzjgsny.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2hhoppuao.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2svxmmeni.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpfkpzcv.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2todrlkwz.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2knuhymzf.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2ryvvyvnx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmkymjbo.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gt2bxxiomxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2vdgqffrw.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ktnkqovz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gt2qjgkisto.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gt2pomcwlkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2pyzfbacb.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2wvlorygb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2svgysvst.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2sntmaljr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2lyolzsbf.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2szwalage.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2camlstmu.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gt2zpbwkurc.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmgeiqit.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2oqdfawbq.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2lowpkqdk.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2oiexwzpv.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gt2itcjnfpi.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gt2ktywftqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gt2kzkzaktz.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwfutshz.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2wmnzpejh.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gt2eggccgcy.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gt2zrmqtglh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khvnqwhe.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2bbwjuwhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wryxgdgb.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2oqhcross.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfarziti.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2nltrlkzi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2gpojjgrx.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2vmoxxwxf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2szadeyhu.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2fnwpvfqq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2flbjhzxt.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2wvufsmgy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2qzuczjgk.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2cthllmys.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2hjgzagfc.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2irgeacfu.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2ukbiojsk.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2vegfweih.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2ocqybxeh.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmfnowpu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gt2supfopmo.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2jboqhpuy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2mkqkpzsj.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2mrhymwoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gt2ckmpcosl.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gt2udrijjpa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfplvyi.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2hyncnodl.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2gxepkruq.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2fqmwssmn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gt2spqpwdcu.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2tjzqjbwz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gt2grpihjst.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gt2xcigymqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scrbmthf.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2tgvmoefk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gt2npgaayhp.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2pqimrwcv.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2wxbigvgn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2gaspfabt.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2nopcpejw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2eitearab.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2rhhxbeye.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2utrmchrn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttmixrhc.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2mouwtllw.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gt2ioirklbx.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2dmrzswgs.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gt2jgywrars.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gt2obcxonha.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2puddikep.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gt2glvuvocw.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2etiisbhv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2wvoieszb.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gt2suqyfrwd.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2kpqggobz.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gt2odbxbxoc.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2mzrrbdjm.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2damirwge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2wnbaglhk.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2aexuanep.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2urbguixb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mpotqnef.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2cgnrhpqy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vnrtqjia.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2yrhbefcz.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrsahump.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gt2ksannvsu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gt2dvsprrof.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2tenoosbt.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2godulhed.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2hawpayei.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gt2qsdecoza.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpotjxeg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2lmcukshu.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2rnzqsijl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2wfdehnqg.html


<!-- 参考信息 -->