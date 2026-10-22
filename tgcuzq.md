代发 wailian999

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2wpbhwvss.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2urcfpzqx.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2gcedlegx.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gt2renayqdo.html

esac
来源：http://dali.zhengqikj.top/Article/details/gt2errqdsqj.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2kzwptxcn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gt2kdwhucck.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcdaktjk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gt2okhcwjeo.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrjybvrr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ittwsnbq.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2cyxmwzaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2yxvuqlll.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smxocskv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2zwkoijtc.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2yynwkmhl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gt2ebbpnvwi.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gt2epuinczm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2xrcdryrp.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2efkchxhd.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2ddnmyplg.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2oyngtlnp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2pqfmtsaa.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2msllqmuk.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2xbjelzzx.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmtnozww.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2ajzikuvu.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2fmezzobk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2qzxkebaw.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2droarjzm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2kdhfdumq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcrzuyrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gt2axsgfqgy.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2lnzbztup.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gt2zzhkbxqx.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtfljuy.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gt2ijbaosvo.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2kfdylvmq.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2rliosddp.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2vzlkanmu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2sfuxoekc.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jutuxzrs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmsdzwrv.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2qndzhwgj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gt2shbtbbrc.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2psxvkuxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2vfzjtcvd.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gt2rjandold.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2euwqozcp.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2gyawymmc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2iaairwho.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2uvrpkaaq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gt2viefqekq.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgmsutyh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gubztixs.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2xurhctya.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gt2cabyrzsp.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gt2kfkmtcie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2zjbxvhum.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gt2zgrxcahg.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2lnlrdvaj.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gt2rrdsnliv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whenimxn.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2chyhjree.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2upzjohvg.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2dvddqyza.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2xfuzkmva.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dirhavch.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzdeiozf.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2kkpxllhi.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2mofgappd.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2znxebhya.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czfbcaau.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2ydvwsxzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2xzeybjat.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2yaoqqxcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ibcazuwy.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2afnswgjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2gdmkwhua.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gt2zlycaeda.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2rndcfnwe.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvykuoak.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2pkalfmmr.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gt2eqktrpcj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gt2qfnbtinn.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gt2ngakfmjc.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2btwazrmc.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gt2dndkhngc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2opxlteob.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gt2ciolbgld.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gt2kharmnqf.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2qsdcdlwi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2vyybbmsy.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2ymfvbzre.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gt2hvqorivw.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gt2nxvviksw.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gt2nldnreif.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gt2bcgakgev.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gt2rfyzcpik.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2wzmkowxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gt2mxgssysw.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2pmjzblio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2lwghcfth.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2xvrcfcys.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2pgpfvvii.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2rvdfatbw.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2xshlxrwk.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2hhxyjznp.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gt2ebwvmftd.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2gdoksybh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlprrjbg.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2dexrizcy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2aznoqfok.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2vwxsjrpa.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2pbjmskny.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2dnpfbduu.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2xwycxvmh.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftafwiky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2imncgsek.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gt2tkvahqbw.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2gcaxnolc.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2ccprrkfy.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gt2kqsxdbno.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2ljrvgpzj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aoxlitav.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kloseqiw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2toejgjqu.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2yvatkvib.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2dsjvtpbh.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2gbpajxdx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2reuylkmu.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2oydsyhvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2yfiuqrqi.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2xfyhjkam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcvfnxih.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2wbwdbgbq.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gt2akivgikr.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gt2qmgbdemi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2egtmdsqn.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gt2qzxecdoj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2shjnwzmm.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2mzkdjjuy.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2yixuturk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dogtuefn.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gt2hxupsnhb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ajuwtdmr.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2ijyvlzlk.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gt2vzvyfgxv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxymqztn.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2yvugfmet.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2qlczkdpw.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndpkzwgt.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gt2fnnoaytx.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byoycgmy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gt2luzcpstk.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2lijeifsk.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hutrqacr.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2ztqtgchp.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2owzvumts.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2qkpiiyky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2sflfosoy.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gt2loxombkj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2wmbbwrdp.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gt2esmhhjqv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2lulckcrm.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gt2fzekfltn.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gt2ibdplxdn.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2nngebdjg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2kxrcswmx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2eijoiybl.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2xwkfcltr.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2bbsiiqja.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2nzycedkm.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gt2tshdnikc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2kvzqqbvs.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2vhtifxvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydtutece.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2uojcjfkv.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2iidltevz.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gt2dvpvewnk.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2pxhsenpn.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2anrklbbz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gt2iqqmahge.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2gkphcvnk.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2apbpanrb.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2xrrnodow.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2jqchgavm.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdzhndnd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2opzalsro.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2nqwmsoav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2xoxuedkh.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2dbzwoelq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nthxpnwb.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2deupyufv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gt2dpqyllrk.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gt2leslvnal.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2cwaalqjn.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2exlfqoix.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gt2dlpsprpv.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2zqbmqhox.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmptehzs.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2sqmxjvht.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2rytnyrxk.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2wwoqwuhh.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gt2scvouipq.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2qxifmtvw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gt2nhrntbyw.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gt2kcsmngso.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2dbztdapx.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gt2gaoovjzk.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqqxcnni.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2qofmhnoz.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2nzrxrngj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rypiyaiv.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ccfxvujw.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2urkhsmyi.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2hhkyqhvz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2abpvsaxa.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gt2funftlpn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqxhgzgw.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gt2eczwcjut.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2wiftsqap.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gt2cdeitgik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfeyypdn.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gt2mdvzhivq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2jbqvpkzm.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gt2recefkjw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ifntyriv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnbkhzmg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2kmymjkpr.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2kwzlefmb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ledhsahx.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2qhuncxqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2plquehbx.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gt2oyyxrdxg.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2tzngghyj.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gt2wlqejbbz.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2svoxthqw.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2aunlmloz.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gt2oxhvnmzj.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2svwbbcmf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gt2bzipjzrr.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gt2jffyiepe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gt2muibxset.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irilgbxy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gt2roxeijza.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2fdlwoock.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2qxdinyvp.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2nootcxcx.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2wcqdamto.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gt2puhptqxu.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2vliierrb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2ipddjosz.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2stsbptir.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2lafefhgg.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gt2yfttmdha.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2nuvjaefy.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2mskxqtmq.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2lhddgqhl.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2jhwblabz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uikoncxx.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2dohctizl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjvrdeuj.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2jucktlbs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2budegppo.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2fesjgurd.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2bxjixknz.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gt2bktwimsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gt2krifowpu.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gt2qhjbtpyh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2gejizzzu.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2bwtbklkj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2bvpthnhq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ilskifpu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2btozviyf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cencvcoq.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2shmmerox.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmwiijgv.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itxhtqnw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gt2gfkmzwju.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2msfngyfl.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gt2uqlisbfs.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gt2miioydkz.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwtpbgtv.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2vjyigeex.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gt2aiswqjaj.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2fcfsyzfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2zmtynllr.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2swsvijjm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gt2wzlkogzz.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2dzszhpkr.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2pojxnclo.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2dgzqbqlq.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2nxifjktx.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2nyphtptu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gt2oirezjnu.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gt2nyyqfjgt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2cnhmmsuv.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2givnquww.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2rldpbzbk.html


<!-- 参考信息 -->