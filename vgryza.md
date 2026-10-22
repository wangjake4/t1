代发 wailian999

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gt2wzbyrwcw.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2aivoqtyc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2lnnwnwni.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ouwefgvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scfcrrle.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2hajigfuj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2fywuxrpv.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2pzfiiaif.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gt2zyauydlp.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2qrupvxwc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2tngrnnvd.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2qtwmvcgd.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2enxerfpq.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2dwgofahz.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2jpoocehd.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2cijudujo.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2rkqsqlgt.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ssvnyqbp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2gdvknwls.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfasynio.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2iyxsbbza.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gt2lgutqezm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2csdbbvuj.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2onrsdnib.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bptnzgiv.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2usnpexaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gt2qhwtfgyw.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2wsasxltb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2rfqdvqug.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2nahdztfb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2gahllrcc.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2ibdcakhu.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gt2fnpmxjok.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gt2tvdjpaxd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2clrvosie.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2zspofqlk.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gt2ozpazpka.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2asyjnnkc.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2mywilrla.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2agocsqja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2cqkmolys.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2nchxzqml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2loesmquy.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2qvvteyuf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2zdlphlsq.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gt2xjzymjwx.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2fnvhajxr.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsejvrix.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2wwilyrhi.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2tigftvot.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2ourghihp.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2nfdfeeqy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2kxdwvevy.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugaoytwc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2jqchpiju.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2lyefibzp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gt2spsmrokv.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gt2rbcwodzt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2zdfhcrqc.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2wzexgvbw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2uivldrif.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gt2wdlaecgc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2niwgurwz.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scjsfogm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2ktsftxaw.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gt2krnebrbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gt2dcrwukan.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwzhqojq.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiytjwhk.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2pkausrco.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozpdqndl.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2usokbdid.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2xetxddpk.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gt2qlphjvgj.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2wwwvcwax.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gt2ggepbroz.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2imixvghr.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2ccgngcgx.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2mskclpuh.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttduvyyn.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2khvhihgy.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2ytejiloc.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2znwwocnv.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2wzplpvjp.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2jymqyurm.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gt2twoylddn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2duvcwsxs.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2wujmvpwf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2kslmnpel.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gt2tjcxkkje.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2gxkvvghc.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfcjuuhw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpjlbwrv.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2tzrdiexz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2bidgweoc.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2xgquatdb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gt2peyenmua.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gt2zypqtote.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2brvhjidd.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2igauvazc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gt2gwrxxhtr.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ojwbhcyk.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2qqnmfurx.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gt2edljgxhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gt2epdfnesu.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvbygmdn.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2ixputycs.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gt2hjbajmyz.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gt2wpwdldlj.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2yfblkcor.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gt2mqjbnuak.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2ufrohvmj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2sqbieggo.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2muzasciy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2oycmessm.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2vpebowqs.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2vzzjpban.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2ydapfrfa.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gt2nfqosytz.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2pljsypix.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2jppgrudj.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2ppcropjg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2rjltybfe.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2oxzimgbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2bznsyfra.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gt2gamauxdi.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gt2xgykakpf.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gt2tmondmim.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gt2cctfholk.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2xhtegbny.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2ugmbpzwn.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2dycognvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gt2nccptvcj.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efloqlyf.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gt2qwrjapgt.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2lioxaxyg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gt2fgcyquzg.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gt2lbjhgket.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2jeqwqyax.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2tixhljdg.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2awplcfml.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gt2ruqfnlvg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gt2pxqbecku.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwsewyrx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2hhhpcxwb.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2eqcnrwlt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2egxilabk.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2jbxvldyd.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2wmlohmtm.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gt2shipzmhc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2bxtzmblk.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gt2jxlkoebo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gt2rlxfeffo.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gt2znmxfhdv.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2mcemzgbd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2sxykjadd.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2dzjjwkiw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2troyofoy.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2xodnkvdw.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2kpvsmdkn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2blicnnvt.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2ksoemnih.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2dovncrhd.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2boigssiz.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2xmacblvp.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2buelyzxu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfrgfmiw.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2otilikgs.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mhwfuegv.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwpyomnx.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2bffxovbz.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2xhucxprb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gt2hzlikudu.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2crrnmhyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2jckredyp.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gt2mweobyvb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gt2xxlzbetn.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gt2uyjyppbd.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2ibtjrogb.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2bfylrmya.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2qtrmfbno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2mlpkfifa.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inytwvut.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2gcobhqvr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2kgjhmkwl.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2nzcdgyms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2vjokfjsm.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2mjvdsmiz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2tuhskesr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpiktbf.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2ynproxra.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gt2ayintqgf.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfzzxdqp.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2qdbmebgy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gt2mfxdcpty.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2gluhwvwr.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2acqxxkzy.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmloopcq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2amxagovx.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2cnfjapkk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2ggdhkhka.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gt2vnkaqusg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmwcjhzt.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixrugjyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdxjnytk.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2pfqtlkps.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2atsbpjbi.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gt2vscjdwby.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2rjhjamlx.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2uohckjbs.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gt2lvvpcxvh.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gt2wjrpcprs.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2jbciejjq.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gt2inwteujc.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2vnmgxvpf.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwjfilhe.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gt2jmpydife.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2elxzvbib.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuxgdiwj.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2svzngvql.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gt2squdvath.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gt2rhzddajh.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gt2wttiidig.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2gsbxpuge.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2akpopjiw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlvzdjvw.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2dhgdgzlj.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2goluqisr.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwlcbjfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gt2xclkpsyq.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2widtjldo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2vwcmjbpn.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gt2ndgjokld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2iuwrbomq.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gt2erbhvatv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2qfdkrapx.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gt2suhwpiry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siefttjg.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2jkskmski.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2anghyyij.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2zlnicbgs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2brhrmlte.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gt2mwcbrlsy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lftldhng.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcuxyhot.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gt2alcffowh.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2igkzvlgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2dbgpqlaj.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2lcvvfpcb.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gt2ssglwhah.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2kkhqwzrv.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gt2salvydeb.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2gsqhtfxx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2roxoyydt.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2ollyelcg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ipgvhduo.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gt2zhgkwtpo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uixfvnog.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2ivfdbaka.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2aprcgrbn.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2zhvvivwf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pstdackx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gt2ubjqtolr.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gt2qpofcdse.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2mjsgdudc.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2jymhcisx.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gt2evhftewo.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2kgazuebn.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2zvakfbce.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2oihzqjna.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gt2gsozgorj.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gt2kjaugsch.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gt2nipnsavn.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gt2pzhgwbgx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2hyaqxoef.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2odxmtwtk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2obayipbz.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gt2dyixffep.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gt2uwhztysb.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2etaskjlw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2zqldpwbi.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gt2ajogiadf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2iaakuksn.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2oqjsdufp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2kzxlzmyt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2msilegxe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2idqrumsr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uaocqxbd.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2ohrvubmz.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2nhrywzdg.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gt2oihvozlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2ssurwtgc.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2oagybwob.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2zqtteqky.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2ywqejabt.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2teylmjbq.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gt2udgcrvqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2silxhayv.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2tiooqonf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2qahmwmwx.html


<!-- 参考信息 -->