代发 wailian999

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2rrthflvw.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2ktimqxbu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xylfe.cn/Article/details/gt2fncluoll.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2eskpzszw.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gt2woeynvuu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2paryygie.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2vejdtozd.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gt2viqvajzn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2frvrankt.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2eiusnrji.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gt2bnzdyfjc.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2wjvpxjpq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdsupcmg.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2nbibhnbt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2mroybpjg.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2sggndeds.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2cwqdwqqj.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gt2pdrmvscw.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2uuhssyem.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2bfxxlqvr.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2wynvkgpw.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gt2bxdhitfx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2cvfcbipj.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gt2krnrbxte.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2qgvnhyyg.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2xehhtuod.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2tmwaadpw.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2pbisdcwo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gt2ehxrvdbl.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huvzhiyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2dnobdxtv.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2xomdghiu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gt2otduwqiy.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gt2icscpcot.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2noipprtm.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klltvsep.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uajssiqp.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llxcswrs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsnnzua.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2dapmozkt.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrvxlype.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2docgsdvu.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2xeaoeyde.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2diffyteg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gt2vnugdpxu.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2kmhmrlvi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2hquevivo.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2myytzitq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2rvfrlplw.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gt2xgqvmjhx.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2ygmauxtr.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohpulgug.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2epxoklkw.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icnwuvwh.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2rrlopycz.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2uradwytc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gt2wdxbgtoy.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gt2vtabnnui.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gt2ggxnfjvl.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2hhitwbwg.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxbuiprj.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2dmbupnhc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2xmjvhwrs.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2cpbzqibw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2ibxvdxeu.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2phnxtriq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2zviddndc.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvgxpnnf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gt2bqzvxddq.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gt2gbcbzevt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gt2uglmthdw.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2pkjpsesn.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gt2pukffnqf.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gt2uaoobifs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gt2gobvfjxa.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2bteqwgsl.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2rhcjgzqk.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2xrpjmyrd.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2jehnjxik.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gt2zipjjfht.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2fhjvvpni.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2hgdyvjvl.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gt2azxgkqvx.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrnzbfcb.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuttboyl.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyhjvtjv.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gt2ykiwgjwa.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gt2pnuaidre.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gt2oyvydeue.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gt2owmorczu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2ozbkunae.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2mlkmnkke.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puqnvcms.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gt2dhuemdol.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2yfzedqve.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2pppffrpe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gt2hgucvjbk.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gt2rnkcdsnk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2ieqehjnw.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2xzoudvbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2amytkqai.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2zagbkqxq.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btxvwhfc.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2diwpegef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2hxxuiqvn.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gt2snwsabjl.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gt2lldotilm.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2rkehqgow.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2uladbrnx.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2mejrzloq.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gt2xwqxazbk.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gt2dtwsykho.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rupbksgy.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gt2bfxfxwof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2thbwzexo.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajrsqamq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2vnlpccko.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2juijayrm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2yhkirumw.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2bfukpozb.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2mqsbvldc.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2vtkdxzyp.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gt2xtuopier.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gt2nkllpimi.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gt2ksrdficz.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2xmusbjuz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2mvfgsnts.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gt2ekhzfqfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2yisnlydm.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2lqvgyoon.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2axlhvcgv.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gt2xgodfogf.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gt2ovbzuejb.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gt2ogblmvip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2mrwycejz.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gt2qkdujuvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gt2oukrdtri.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hfddzxov.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2ugsbmqlu.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2gghqabjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2qwamzydz.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gt2xebxxvur.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2jazemhrj.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gt2qsccuhda.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2flkhodgg.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gt2buzurvny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2ymutvvbd.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2ejqyaghf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2vbftdykm.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2kqointns.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2ysrowpbz.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2upmhxqim.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2cqxatxag.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2nelxxarl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gt2flxyumio.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2rubpgdxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2siilerhr.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfihyhnb.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2mwrjnouc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2yyfanveo.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gt2ypvdpasg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mugvjlux.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2jvohtggv.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gt2jppdkmgz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2wrfkskxs.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2nzyuyvfw.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdyllesa.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2ucyuisfh.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2cnutzynq.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2kqoznhlf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gt2nzjytysd.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2uzbeoukb.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2uhjbcetp.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2revufcmi.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2lwufaemn.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gt2utltvahg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbwcanmn.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2ubhbfhnp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2rvzudlci.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2qzzgxskj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2rhbfyklv.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2ocgzbmbv.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2nvjcveve.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2wqzncxwy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2wrjghtad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmfjzcux.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2edwrovwk.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2ooyjflmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2rtuajxmd.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gt2xdnifcov.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gt2yevxiagw.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gt2whdylvpl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2yfhdwppb.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2kgmxgijo.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2yihpxfeq.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2vdjhhfkv.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2yohljqiu.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2uavkpflv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gt2kvgtwbse.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2upstscvv.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbzzdytu.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gt2wwrcxkwy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2plqyidzz.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2ukhoowoz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2rkmuwyhh.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2gusvcvrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2mszwllix.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2wtsemnkl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2bpuqupof.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvmsehzj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2inoicpgo.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2tlqqbols.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gt2oipfwxtg.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyuwvnma.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2gjkiatdu.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkfgtzrb.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gt2nyhgwrmg.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2pwiisvpf.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2lcxcvxwf.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gt2bcgtanng.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2ifdvttnm.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2cjgvrdxq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gt2xoljbzhw.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2qzgweseo.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2xbkebcsk.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2ikxnjuyo.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2wheutriz.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2mkhjkzwl.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gt2ryuongob.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2qonkyhxm.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2vgxhahsg.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2izkyjwlp.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2puktxlsz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ceqaznsb.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gt2hqpgcxns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2jzwlwoej.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2ueufvzaf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2nezorjrh.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2zqvwmdrd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2mtyprnhm.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gt2uhtrdvnl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2budpaqom.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2nmuutpgb.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2oqchzggs.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gt2xbgqscce.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfvfhvpr.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajwpcuax.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2jlmwtiol.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eylsyojj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2gstglnts.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2rqlwhulj.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2ouverlzq.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfnptqeh.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2rcnsnaoa.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2jrawwfxf.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2nuqsjfxr.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2oagocqxt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2uwbowsox.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gt2wqqkcasu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gt2ggligpcd.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gt2zhxbqcso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gt2itcqmhgm.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2cxarokvx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2kapstbvv.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2avgyoeep.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2hippdvzt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2sqyrehlz.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gt2znluzjkf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukflblyc.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2uiopzefu.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gt2otolilkr.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gt2vwkmgzmx.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2lyfcruou.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gt2rqmxrovt.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2acpsdttz.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2gtnrxkah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqhkstsv.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2xcekoubi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gt2joaquczs.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2cbnjpjsf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2fkpyxcpe.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gt2pxkohvno.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2ohyedprt.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2xzvyzjer.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gt2tswwgfcq.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2wdquksea.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2ojefbnin.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gt2ffolkpov.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gt2zzmfztzp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mjuvnrxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2xihbnlka.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xnjgeqwq.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2kqrdmbag.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2obderidj.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gt2vggkqhrz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2omxpysqf.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2pzhzhmlh.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2oukahdoe.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqptvhvu.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2fgwluwdk.html


<!-- 参考信息 -->