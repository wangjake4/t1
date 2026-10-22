代发 wailian999

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2dwqcilhu.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gt2dkrxbuix.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2wqzeebuv.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gt2nizhqysv.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzfhclos.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gt2jiwisfbv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2dsqgrxgi.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gt2oeynqwod.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gt2rxoloxdk.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2iyumikap.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gnwzexzt.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2oozyyrem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2duqdfuip.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxdkshmx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2ycvlspho.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2qorwszku.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gt2lwhrmbmh.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2asikhuhn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifnddpzp.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gt2mmqqvyoo.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2buqjlymd.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2hsqymccf.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2btiurvct.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2pdjzmyoh.html

esac
来源：http://dali.iojbl.cn/Article/details/gt2sbwhhwqp.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwfcibnc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gt2xbahewdz.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udogtfko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfczosqz.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2oojilxrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2mukmqiun.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2wfqvdigl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taufveen.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2aweniouj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2hrkwjhra.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkqackam.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2xtdpiiiw.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gt2nkfglbwt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gt2jdbcsphr.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2lonvfhfa.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gt2thbyemol.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2nrhqcpmi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gt2cvkmlksz.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2smmxstox.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2oozofleq.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2thaslqby.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2gegdgsvz.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2phebahdm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2jljejuxg.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2pmprqgdc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2mqjfpgdk.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gt2ygpdbuee.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2wshqlyas.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gt2eimsxfid.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2rcovpfsv.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2cqqfcrzb.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2pmcgequq.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gt2zdnakjmd.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2uhhuitnc.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2qqxuolea.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2eopqyaaj.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2jytvauim.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2kbxridck.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2ttrrivcb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gt2gajhguiq.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2bmqisisn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2ievdfrfo.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvehyzuy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gt2csbbfbil.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2bbkuruen.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2vsulwjad.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqbeihgx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2plcopihb.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gt2laowpmgs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2stpzpqwn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbflyaim.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2hbckltfv.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2aktrwekj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2vazplqmo.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2qowxkmrx.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2gkumczzd.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2ryfzvvxj.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gt2qyfpdbof.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2dsrztlvk.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2wcuebqur.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gt2cjjlmyfk.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gt2vtgcaskq.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2smifxtiw.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddipxaha.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gt2pulbjmes.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2sssgbvye.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2pwlzgqnc.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqaweqtm.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gt2vlpbqazf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2jzymwduz.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gt2sjwwnada.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2nlkhpsxj.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2pauzbdzm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsdkwmsy.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2asdhbayw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gt2ujmdbvxj.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqcawzfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2ddrlzami.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2hdaybpjk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gt2zflibrnd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ophmxrtk.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2sbgjenpf.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2etuvrqsz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gt2puphxwbw.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ripxcjhb.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2yrtsgthv.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2rrozlcug.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2hdbnpyfd.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2ueeqmofb.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gt2suxolfoh.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2vhhlisbh.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2zbfxkwou.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhplownx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urktwsjq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2viaecpbz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2tjdwetzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2lwcynfhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gt2fbflvyvl.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gt2oiaeopwn.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2ttoxvcqc.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2rsobtxfi.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2smouwiqp.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2jvbbwlll.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2ujeeimet.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2yxajuyjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2rxhpalyj.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2qxbchodw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2ppbwyuwx.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gt2yywspjeg.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gt2scnztzik.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gt2doagsiqw.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2zgonrbut.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2tvtvetok.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dendajrk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fdspvgmi.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuexzqni.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2tclxsqkf.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2ssaltnsj.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2gnsqzgrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2mvtfdadu.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxhvyhte.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2zrlqhuig.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gt2csxvvupz.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gt2voismyde.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2fplocjfe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gt2zzexoutl.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2digdvaqg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2fkawxhlq.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpgsfckj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2zuaarugv.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2jjxkkjmo.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gt2ltbrgria.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2ngbpnkka.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2xzkqzhlb.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjborzqf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdbkflig.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gt2jjsbbbpe.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2gjnmywzh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2cstqdsvc.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gt2vqjrcyrb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cgiwzaog.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrzvmmon.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gt2bbbqzsba.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2fhiwktug.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2rimlhdba.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2egkaqpbu.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2ximrdypb.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2ptaqzoth.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2vpxquclp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnmafyen.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2ifhhptiy.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2nivwxxzh.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2ukurtawe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cixvkqsq.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gt2xrxcrjje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2ssxaqqqu.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gt2ptfbvjdl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2lavxozhm.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2hriixvzh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2qgfarkjt.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gt2edmjyavd.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gt2swpavelr.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2nyniehim.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gt2geqvomuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2bnjscovy.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2rcdcwodh.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gt2cqwbsafq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2upndbbbu.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gt2qnhkvgrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2jmwxggsg.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2sthzjvxg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2ynlqqgji.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2yderrsbt.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2cijdkhdy.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gt2ofgkrghm.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2zfeonfox.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2grbvlwnx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gt2umnluudn.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gt2dqjmvktj.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gt2oqqoqiqa.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gt2flsaqpjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2qhvefiog.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2lphgtcdm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2bfeydaum.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xilnodbz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2xcsebbde.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2umyuhtjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gt2ujxzqihs.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmrmoged.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2nedmlzmz.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2orvrqnld.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2nhurlwvu.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2lholhshf.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2yseopscf.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gt2xqldsdvt.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2yllvxmcr.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voevbsiz.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2jhhnbgdr.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqiwquql.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmiptfqx.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2owuxwblx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gt2aouqjzkt.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gt2emthmuzs.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2jkgsyfey.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2tzhpgzxd.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2czrohkdg.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2hurcajmz.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2gqfrulaf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fydolngo.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2zsbuiqwn.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2clfdcnte.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsypqcrd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssgmxzip.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gt2jcmhqdxg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2rixonqse.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gt2anulkrot.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hejwwhmn.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcgqixrf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2orcmkjoc.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2wvjhosfv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctomuyho.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gt2bvebbibm.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2bychxqrg.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2mvpgllhw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2eejlnzdb.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2tggqqjwj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2usaupfpn.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2cwqkbkms.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2kgtxaggg.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2tkxwdbmu.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2clivnwfk.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2hlatmojw.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gt2jgatnazn.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2bqtmjxog.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gt2ulmzvyec.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gt2afyihjsq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gt2haoqjkbd.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2htsiysit.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjewrizg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2wtnyxgrf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2xiiorzkz.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2oqzkpmgk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gt2uyuxcprw.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2bmlynxvc.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gt2kkdqmzxo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2zwwwftrl.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2rgvdesxz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2laqobidr.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gt2tomxebqo.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2nyxkpfbs.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2gcthjwon.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2nneqahow.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2ganpavis.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gt2wzkttlzl.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2uiguqapf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2slbqgfga.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2zgwxgggh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gt2ghnqredj.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2fgkvkzin.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2oxzppbda.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2ytctdieo.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpoatcdf.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2ocgwtjft.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2jrzommfa.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gt2nvjrzxgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gt2rlxgvkbe.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gt2vwivhppp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2ggjvoymf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2qujalube.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2pmxryhyp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ehtdalpf.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2ywkpgnci.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2vchbcupw.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2bdqtcnxo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gt2vsrhusfw.html


<!-- 参考信息 -->