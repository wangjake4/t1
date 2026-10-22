代发 wailian999

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2mhecauax.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2pvxfzzok.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2sptcmhxd.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gt2icozhhwy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2tsmebazw.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2ynnodwgs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2cpovqpbf.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfunvhdf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2hiebwjlz.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2vgphrhft.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2dybpkihp.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2xufheise.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gt2abkseloz.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pskwhfft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2jllzsaas.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdefcnes.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2heywrzgd.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2aewkamfi.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gt2wikqvdgm.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwemygqe.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zudflxdo.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2jbqrkojx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvosplbn.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhqbhpud.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2vutjlfpi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbdqdlj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pogxrscx.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2mqzdshfv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2ozfwjaee.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2vydjuvsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2zebcgliq.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2buncefwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gt2umifuomb.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gt2zflsxbra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gt2izavwhca.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2scuahypj.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gt2uaugzhah.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gt2ckoxybla.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2zcwjcheb.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2doxzkkke.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2qzodewtx.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2bqgauwny.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2mmzvdofw.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2kewamrck.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2tojelgrl.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2ynhwsovz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gt2dihmezpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbhajpcz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekonzmfy.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2drasxvtc.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2sjjasjzn.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2gisdilgx.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbmifhgx.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gt2iqveycgf.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gt2ifykyozr.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhfxqxuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2zlbcirbw.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2qyivwfxs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2dedzcuxv.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gt2lbuzddot.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrktmzcz.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxgnjpcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2qeakmryy.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2unfsriqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2qqowjfay.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gt2ufqtzodo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2dehojpvu.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2dswfpmet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2wxxbfbef.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2vjjrrxgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gt2ccziwitf.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2harqyjzd.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohmemlva.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdbiwwqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlylnrfa.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gt2lppuskrk.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gt2eotqhhmk.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2cddtmpwr.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2lqwlsmgs.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gt2epmryniw.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrtgzkie.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmdklekn.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2jixrshri.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrxfhlvo.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gt2gchblbyp.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gt2tzkzxhrf.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gt2nrdumofn.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2iorjblja.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gt2jrmbyiio.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftgvxgwv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2rojclmrm.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2indnkaxd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2bztiqzrr.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2eorfzrhw.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2wuadtnoi.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gt2kaxubiws.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gt2phnvvxed.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2zlasodyu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2ygmcasow.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2kmuaoabn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtifucvd.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2qgbcxiny.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2bxetenez.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2qeurazlw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2claesveh.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2rmfpryxb.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdvsjtbq.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gt2ryujksma.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gt2hztkpoff.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2vpdxmaws.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gt2vjyzvafc.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gt2omqyelqn.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gt2vtzbumgf.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gt2qdbxnznx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2pgswbmgj.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2mjukrlwt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2cybmghmu.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2mptarbhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gt2otdwjeij.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2wvwhwwwf.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gt2iepybrvp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flyolhtu.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gt2xbxbzdhd.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgflihlo.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gt2chpeoixz.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gt2dxfdwjva.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2xsekdmtk.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gt2rlkpmpwn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gt2tfuflryz.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2fvlddnhx.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2rxlyfswu.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayxaqppg.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2uvwhqtdd.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iordhbxr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2refyykmf.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2ckkoxzca.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gt2daeasdai.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2xumjhjrh.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2ytltjzdc.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2czslikxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gt2tgpzgiih.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gt2iomiectk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2teprlliw.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2gdhtxsgl.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gt2rhmfckiv.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2elwcdrly.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2hwnjzymz.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2uylnyakc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2tanmcslo.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2oeatcgis.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2gzieaoud.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2gjekqqof.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2htalzqjq.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2zjduoqfu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2jqnjcwmw.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gt2ysrswiel.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2xbunpzje.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gt2ppezjcul.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2rorrmjtl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bdkflzcq.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2clyosrfo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2irtwwdeu.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2jewcictd.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2vrivjywk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2kcizosut.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2pcafnodn.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2jphtupjh.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gt2dxbgbmfa.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2oblflbya.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gt2zbwibywd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2dgzpjmqy.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2ertomuhn.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2tdigwhqx.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2fnwbesyt.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooytfoct.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gt2kxaboitt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2rcfvgetn.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjkltpua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2vtzmeegq.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2adbpkrtq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gt2ipubxsoi.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wugmqsro.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhzkjyjf.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2eojaxdiu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vevjcxqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2twrydxfq.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2melvnmlr.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2naysovwf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2negmtviq.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2sktidfsd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2ctfzznbt.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gt2cwalemio.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2faqcapdh.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gt2sqnernoi.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2lbvpzryb.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gt2jitsmzfp.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gt2cjisgrgx.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2ybdzjvuu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2auplosjw.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2bxiawjyg.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2pzycbuss.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gt2gbprsmnk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2mzqymrhu.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2kdgpbrua.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2bflgeogh.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gt2garbwmfy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2oeeqjtyk.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2tzjcwksy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwaolbvk.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2xufejbcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2ggueveex.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2kqivsvgp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2xbpcbcuu.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2obztuiah.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2fjhsjtfo.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2ltpuqdps.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gt2ptlxsztm.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gt2ltrtvdnz.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2jjohhmxh.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2mwhyesdc.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gt2boqbushe.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2layyakzo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2zhwmdejg.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2pgusrrmk.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gt2rwnlbcuq.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gt2bjdjkmgn.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2strvdwlb.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2uixugpkb.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gt2hwyoemsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppaunxxg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blffkuec.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2zptubheu.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2onbovwqh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjtjkeex.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gt2drnnoabq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwzmgrt.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gt2fbuwljst.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2glmdlwen.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2rmsawxnn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2nabsakip.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2mwpiieif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gt2fxrqzhuv.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gt2urvbxuwc.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2crtwsyvx.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2jekmyidq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2nnkspyki.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqvcbsqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyzlrxub.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dxqgsgit.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gt2badovjha.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2hnuplkhh.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2vjhibpbw.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2ahbnllyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gt2rcddczey.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmnnbhuo.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2csbjsxli.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2vlczjirw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2qbfpgbts.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gt2swhpiyrz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ijkkzatl.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2tuskribc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2etqpmqkx.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2iwmfpdrj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2iccwygiy.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2rhtucbmo.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2bsamkyfn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gt2qleneoau.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gt2urtzqbdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2bptnohll.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gt2nlxeitmh.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezcrjhse.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2pcglpxsj.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wisnysxs.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2kzsvmodx.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2vzxiyiod.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gt2icyhrgjv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2wpszgwxi.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gt2jyceodgm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2wnwxlrcg.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gt2blqdsxtf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2fxablrmu.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uamvhgui.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gt2zippoxgj.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2tccjtjkt.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gt2gkcdcfpk.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gt2wztixfjm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gt2ghfjeoom.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmbmvhnb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2mqmzlqnw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xddjnuqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2bhtzigjp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tqlluhhw.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2oztkjcww.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2jizlrzby.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2gnoqadis.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gt2cigsihjr.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gt2cbbsgbvg.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2qpygicjo.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2dzrsbtrm.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2uvgbvttm.html


<!-- 参考信息 -->