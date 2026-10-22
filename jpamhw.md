代发 wailian999

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gt2utcbaybi.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2dldxqfzm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2prdjqbrk.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2offyykcx.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2vlsjkfiq.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2bbkkzyrp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2zscicifi.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2jnjzdnvh.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2fnvibzfo.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2buuzivwn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2kvyerzaq.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gt2lzsafyye.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2kihdydrm.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2dqmeadlv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2gijhsxvi.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2ccmtvcha.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gt2obbkwmol.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2impakugw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2xrfstbnh.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2nfoezvub.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gt2drzpcpye.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gt2fvjtixhp.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2ppotqlru.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2achywggy.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2pbytaqwt.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2vagxmcyi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gt2ztzvyixy.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2qaeewhmz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2togsstgl.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gt2zppqjwwm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2ocootdmg.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2bjlmiegj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gt2sehqoxmr.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gt2tvypufek.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysqguafj.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2jstpaypr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2ktavzcbh.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2dugnnvno.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gt2eiykvsfi.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2onelpmyj.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2ptgcqyfh.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2jfpgcyek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2jvqoiyvj.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2fpsdqeuq.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2qmusdewi.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2sucmktmh.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2dmoxijre.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpzrubeo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyzgikva.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2edobzfyo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhfujdie.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2oaeqbkub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2dwmhlivq.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gt2lzapszgr.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2drcgbgym.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gt2fzjqjrea.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2fgduxsxd.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gt2kryuhkyh.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gt2ziljvvkf.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2fgkbrffg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2oosditzw.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gt2ifxihhxx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2qvajqudz.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2qjwjzaha.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gt2ubkqkido.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2qmedacft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2siaigtuy.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2cjtxkmft.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvwaveai.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2rnzooaay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2kqzhksaf.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gt2onvrqbsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gt2lixveabc.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gt2xoucdqun.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2xhtglnzc.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gt2mjigyibq.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2xqgwijft.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2qbbburzb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gt2xsibmfsa.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2ivatfdpc.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gt2khukeegj.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gt2mfjhxkwg.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2nrbdrlxz.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gt2izroxpqi.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2xmxgncfv.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gt2bbqsvcqz.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzzvnpxw.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gt2vvblphdu.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gt2ujbpknfg.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2zbaeqyoz.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghuwiekx.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfxifhlq.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gt2mdoxgtys.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2zfwcounm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gt2tfihtzwh.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2xqliceyl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2yoexvxcz.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gt2mfrmlzkb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2fctbbcrl.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gt2trvvumtt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gt2augiwgpz.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2mpguutkc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuzhzedc.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2fblcuusc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2omaonrnd.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2wqhsgpdd.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2otawmnuc.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqysnzpd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gt2mrdcezax.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2liiqfvgn.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gt2jfkfywjf.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gt2xdwzutop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gt2szpsiycd.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gt2ioujfont.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdilcza.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2xdxgcayn.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrzgxcvf.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqqjkzzd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gt2ncvpseqy.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2zuxdsreo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raaronfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2txhbfwba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gt2elybzibq.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2hrvineoh.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2ntolquvw.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfxdqnnm.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2qsgjzclg.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gt2zpgtgaou.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2mvuyfqwm.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gt2uktuwaji.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2jwtqvkez.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2phirnmxb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2sjsohsap.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2wegeyukg.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gt2irdalgor.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2wpqfrljl.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gt2pqntjuso.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gt2jdfmrpph.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2mrvvtyxw.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gt2epmkzxwi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjpeavbd.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2xhfkozda.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gt2eesuvtcj.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2ohzbderc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gt2iiexcfvc.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gt2zmgoxnla.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2zgtqqvzj.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlpaiqmb.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2swqxhbkd.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gt2chraotfy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gt2eijwofrs.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2pzyquodt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2vpxilxzh.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2qdbwocmf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2knhkufka.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2fqqrhuam.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2ctqnuvlj.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2qbeqoqqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2pjjmcvwa.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gt2tuxxvvlg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2vdcxnkjn.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2ubcjahgu.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gt2ftdsvhki.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pxiudxhd.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfjwukou.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ifkfvczl.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwwkheob.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2neazkrvx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2lqqmzgmn.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2ztnnaouk.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghkyltfn.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2ioadyvkh.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2ypqytcqi.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2bhtzhefp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2nifjwgxg.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwfuygdv.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2gkndgywq.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2hafjtkqh.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gt2lndukrqh.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2apudlmmv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2trnqaiwg.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vveixeyv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2urvbgswb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gndzaios.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2bxvzndkt.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gt2boddyvjm.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2rkicoyol.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2gdawarzm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2mofaktjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2itjlwmmg.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2uhbuqnxd.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gt2lnvrzxuk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2ingartoh.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gt2ibktyngq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2frnhijnb.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2sgakddep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2mjypobwn.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2gxknnkvv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjejfv.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2ubeqjcoq.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2rumfzoqc.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2vultqubr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2iqphnobo.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2zoomrayo.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gt2davxujmq.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gt2qkqsfhue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2dkyoomgp.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2oxvmajds.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2ljswnwgh.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2vbpyikqb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gt2mlwgfvpi.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmdcuotq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gt2adigvnpk.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2qzxzdubp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2gamvxgjs.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gt2iwwocbmx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxqfpjgl.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2htfkqoqd.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gt2eowkjgqf.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gt2kylcfdiu.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gt2lhtxttdx.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2skdgfnkw.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2bpfptpwn.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2heemircw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwlwwkm.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2xpfrfppb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2mzjaaion.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2gczzxurt.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2butxtoii.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2jvorhgut.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2njbqhmqh.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfbofemn.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgoyufnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2irshwydw.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gt2uiskqxap.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2urltqlcr.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2lylwczju.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2xxqpiubz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rehbutkv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2valyjccu.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnicsjkm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2daqlxnht.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gt2yuqlcteu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfzaglai.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2ufkpbtmd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2gfwgbatc.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2ujmzgqle.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2qphilmfz.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2nttsaeki.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gt2ypttdlpr.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2iwzdpfao.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gt2eulfrzao.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2wjdlygkk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gt2vwzerhfn.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpnvirdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gt2fdiqieek.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gt2skxzlsgk.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2kzkdoexo.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gt2yvuhiwzu.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gt2hamjaaij.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2meqkdslb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzrgqyvb.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2asxbjhed.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2cjqnhpwz.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iubydlhs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gt2ccickfpz.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2lesotfnz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2sojdvxpd.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2mmvjbgyy.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2ukjcpgky.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxviaabn.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gt2czfjfljk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2ypoehxgu.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytpmfzka.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqixxmgf.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2qsntujvl.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gt2avoszksy.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2haeqncnz.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gt2hrxmaxzr.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2bocorrir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2bnnoxssz.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gt2sysdywvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvckjdqo.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gt2bvatvuhn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbllkikl.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2mcmzsbpk.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2yvlzasty.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gt2brfnykuy.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2ysxqkdne.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2jsymtjnk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2fjrmmctd.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2uxlstbhd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gt2uonniwdb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zfcxwrfb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvuxnsyb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qaflgtce.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnhuijqd.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2vkxowdyl.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2xglshvsa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmxrwwqr.html


<!-- 参考信息 -->