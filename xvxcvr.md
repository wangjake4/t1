代发 wailian999

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gt2igxwgahp.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gt2uhhwekdb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2mzmeqfer.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gt2croyxkgs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2qdzojrvp.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2syrhxryk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggplvcqr.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcsygsxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2skyuhwpe.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2daawvqbz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2uydvxgpi.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gt2alkjbnbc.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2zodylmcj.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2ukicxjmh.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2qdrmgjvc.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2jqqqyngz.html

esac
来源：http://dali.sufxvd.cn/Article/details/gt2soeyrfsp.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umemfpbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gt2kcamcktn.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gt2jrlgotjm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2qcxtczzi.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bofgcxmh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2crjikrjc.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2brwsnble.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2noixbqdv.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2hdcrroqh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2atrhywvk.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gt2gvkxtobu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzpapagb.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gt2mstigtms.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpurmqj.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2kbaumfee.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gt2fgrwvert.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2btbhaltq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gt2xkqcuxgf.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2ysghhnpk.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2xgzjpzpo.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2mzeourda.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gt2ozbibyev.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2jgeklezc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gt2uqgsiyvm.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2jyyujfyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gt2tlgbggjv.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2zjjvtmsm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gt2nhsyoykk.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2qvcqjwpl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqpylpex.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2tibndyqx.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gt2znxvacsq.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2jwdtxloj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gt2snuqjdyh.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2vnizwewm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2aftkrflu.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2bevqivii.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gt2klieocry.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2aahtaqha.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2pnhiwbyx.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2wyitfmzb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2tgrfnmxb.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gt2giomxkzk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2pwgertwb.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2zouwdxxx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2vtjttgdu.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2irjvbkoq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2gsutodjy.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gt2jnwelcny.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2ledxynbh.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2ykluhbns.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gt2njwydtth.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gt2yfddwalx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2hgloeudd.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2fuvodlto.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2vlrrjcmx.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2chypqpjd.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2aysfhckf.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2xjdilzep.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2yosaiddp.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2yurrvoic.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gt2fikemwdc.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2bzykalxx.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2tmmwzfqu.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gt2kplwxqjq.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2kibaqbkj.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gt2ybmnkozy.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2ondbsntx.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpofgipm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2pttzvpso.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gt2nmgkhjgs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2lytfrakr.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hndzkmml.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2vupyhuly.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gt2woenrrqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gt2ptoshbju.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2vserdcon.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2tgxerkka.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2qkosyabh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2osocqrpx.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gt2lifmbaef.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2chfczaeb.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2wyulsnko.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2rkbtuzvu.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gt2raotywov.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2ijpwdksz.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gt2aqleizge.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2yhhiefac.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2obqxynzs.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmoyzshm.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2ysjzrizn.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gt2okgjkxdr.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukorhhvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2lqcenpid.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2comnqsnl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2oyukftwo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gt2ugxykwio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2dtdzjymh.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gt2nesgfgjy.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2azfthoao.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukohuywh.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gt2cnmpthka.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gt2ulzbzeuf.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gt2axrzafqa.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2klnjwork.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gt2uwfudkpg.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gt2bpnotuww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2bcwdmphp.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2jiaaspwb.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2ebbvzsiz.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrnktljt.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gt2nbgrtuil.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gt2lgovdzcc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2bpolzppb.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gt2hwefmlas.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gt2lyggnjmx.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gt2jvcxcdxe.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gt2qohbcykc.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2qxoedliw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2uslfrntk.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gt2ilefdbue.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2tpguxgbp.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftrjgcph.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gt2jiojjikw.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2mbqhcoyx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gt2fzeqeafh.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2zdurnlkf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gt2jylhankv.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2qlbuntzv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2jxhyujkc.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2dsdghtlz.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2xoyjzbbq.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2acjdozss.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2dhzoopax.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2sjwzuyrd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2pxanemls.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjttybws.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2skdfstnw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2zixgxsfs.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2gxmwycyh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2tdunakhn.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2bthnwazo.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2mpzeabpo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkcelejj.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gt2arnofpbq.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2ifoyqzyh.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giwvvubc.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2bihufbkz.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2ugxjdwok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2tavvculq.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2xxjfsoql.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibihzuer.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2ubppjxeg.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gt2gdtpribt.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gt2txqudunm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2ktkihzpc.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2docaorda.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjczkhdj.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrnzzlha.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2pwilduxr.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gt2hmubgxwh.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2wqyxngml.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2hitspqrf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2schqkfhi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2mhgmilez.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2gdvmoynk.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2mjggulbf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbkwyxmk.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovxalqoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2rsytksrm.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gt2tebnflqb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gt2lcdmkbdv.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2tdoakbfv.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gt2oycotxqx.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gt2njepfnsy.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agtcgdwt.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2eluprrxg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2jgittfzp.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jssqsguw.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtotsbfe.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gt2fxsiajsm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2rqvtluxz.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2haxnnuje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2mbloxtyv.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gt2otlldiwj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2eaxbkxwf.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2dpbwzwnx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsnbjhlr.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2erajiann.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gt2cvjandvm.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2gvjxxgwv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2srhhpjrk.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gt2bqjijdox.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gt2sobwshvv.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gt2ndgquwlh.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2vzatkjfj.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2qpozdrjw.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2oqdbykli.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gt2lhjrzdrh.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2pmeisxfo.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gt2zsowobxq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2semzyzvn.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2znkmwvcy.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2jbegvefl.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2tipocaun.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gt2dyfytgwk.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2leyjzoyy.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iytvqlah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gt2diadukeh.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2vfcafmuz.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gt2cdqdzmjr.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gt2zytfrjtd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2dwmrimgy.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2vidwmotg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gt2hkrelolp.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2jwvlkyay.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wvejojvp.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2drvahnsp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2awowzwyl.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gt2bttobpbm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2xyfdhcmo.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmyzlpnn.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2itjhdwnj.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2xysvqnta.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gt2lqfwpboi.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gt2gxcyyooi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gt2ivnugcji.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2lhosaeoa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gt2tcfuzdnc.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2ofnywcpz.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2dbztrwmj.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2fpdtrqdr.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gt2zeujhkke.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2dpfzwnzp.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gt2corpzrcy.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2baqlbuwr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gt2dkwwziuc.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbeurrtp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gt2rfmheidv.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gt2qbiodjtb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gt2eusbpebb.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2krvcfqwf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2omspjvnc.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2hnncpouh.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gt2utwnhbxn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2lqhzyhlg.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqakhrmo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2fnzqlgzm.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gt2ppzwykrl.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gt2nsnocwaq.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2zmyssuuk.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnoycppj.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsraqbrt.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2cwfvxhqa.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2ojsjzbep.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2gyopwakl.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2utechofr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2eucdfdbu.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2hlhhghrp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2umcxzjjo.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2qzqfkelr.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzzlkjux.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2dcmdffzq.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2vbndcxma.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gt2ecizkgzk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gt2qpfiolzo.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2zfpewohb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2xcfmbfjd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ajffpwgj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2tqtlsgse.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2komgcxqe.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2eidsduzh.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2bmnvwpgd.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yswdsurb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gt2hxnwasrp.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2qobmupqd.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2nzsefgoj.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2iqnnkbdv.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2hmhfobla.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gt2fhbhxmxl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gt2jqjltswn.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crixczlq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgzerkvf.html


<!-- 参考信息 -->