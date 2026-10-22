代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtanixvdkn.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtvxzdwzan.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtjmjfnxob.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtoylazuuf.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtzcqtszgg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzehtxgje.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gttnfhkrze.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtetoawzln.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduxegteh.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtvojfbqtr.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtzylotmip.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtovetfzxu.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtyaxknxrt.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkeofzsq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtdnawywhx.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gttmnsjmpv.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtomdnjuey.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtuwzprxwk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmlznltc.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtjylblctr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkckjtyzb.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gttrmnzrrp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfzzjzey.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtkengllak.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gthbdrndrv.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtskhltzll.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtmtbxagbj.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtuucekhjo.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrphayhvr.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtootfvdtk.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtabuhgvie.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtidrhtdmj.html

esac
来源：http://dali.yvedp.cn/Article/details/gtmvupmeix.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtdpemzcfn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcekemqcr.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtvfhphpan.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtbvkwnpuc.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtlmtdijxu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtagxowulc.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtptlndrhn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtbczrfuez.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtwgpobsdk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtimuqawpm.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gteincbxxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtmxsmhfai.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtxxuzcrke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtwnjsyrbz.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtkruwnzfb.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtvurhkfmw.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtbfrzkkgv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbobvpehp.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtmaygrcei.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtpivrhxti.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtprlycytr.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnhmqhnc.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtzrtjmwmo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtyihhghkb.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtvntvbquq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtazpepcui.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtxsgoidur.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtlgmcwmof.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtypdwyijv.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtsxofffzs.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtjogeukgg.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gttnpaatfp.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtvsfwsckd.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtvvxcehco.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtxypgtkbb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtrologyaw.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtveeywmbd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtisfnnjgl.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtoxrbsbyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtugmicgdx.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtmkpcwxoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvdzlmdg.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gthdhwitwu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtdrynauph.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtcvzktaer.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gthxrjgeft.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtscrjlzah.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtymoishku.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtytwtgopg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtukatdcvt.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtpvdmdodd.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtcufmyyod.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtnprilpaz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtyoxtcpfn.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtnddvejze.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtksovfhql.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtsoxyczjg.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtavbwpxhx.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtkuzgbwhb.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gthjytypbn.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtrburvplp.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtfkuvjpel.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtsrdcyayw.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtyuyjqxng.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gttxadwcbx.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtehjblype.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtsofhjwur.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgmkelb.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtjjwjpegw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtqngtfcqq.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtmxlftvzn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtiksmlckh.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtbxwbyhom.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gttthzskrt.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtgrgfwnje.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtxehosshn.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtwycxmnmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtpxsyoipn.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtwoziedhg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtwoxllzyj.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtobsktrms.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtdxbxxijm.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gthxiedmby.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtcembobal.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtnuwadyhg.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtqhregyew.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtpmohoxbf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtnsdkkpjt.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtoxwqunss.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtcyqqmyao.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtlkfhqdek.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtqevrjjal.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gttljkgkto.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtgpncsqzj.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtyytzysiy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gthzisdycr.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtwdagfxbw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtqnhtayox.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtmblmblor.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtenryglvn.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtswspce.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtntgdrnlw.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtzhsexnwe.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtjhccgtzv.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtnxssmxcf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtxishinio.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtvhxzacwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtepnwdwiu.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsgmueaf.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtkanxdlwu.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtxqrqpjxz.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtqaiedxid.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gthelduddf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtkmlxzxzw.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtsdryajae.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtbhqypwcn.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtcredkqco.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtpxwrzsys.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtplmtqxnb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtfhueojgi.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtrrxerlmv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtempyfqqq.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gttdwbaztj.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtgekswqrs.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtyveudwpk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtuxlxqtak.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gttvbxzvac.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtfaolyhzm.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gthaxvpvil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtqjhiffmq.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtybcqqeit.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaduzjhp.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtohztuohz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtivnfnglk.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtbxxjqvgx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtqsleirjb.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtzzpejjgr.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtbyrmdynv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuzcrbuqe.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtkiovvmam.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzcmvlcmq.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtvcnbczie.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtxoxqxisu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtlgnhjvbg.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtqqilofwh.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtenefduip.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtnqjwryqh.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtvfeybiqj.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrupzedb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwjbzqqj.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtonyjqqdl.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwsjblzwt.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtanakkzse.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtvjevpfek.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gthaahfgdf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtkamcalws.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtgfhrteyh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtbtcedvjz.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkuisebp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtfzcswypc.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtgotbibdl.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gthcfugtfr.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjwbrzth.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtpmutqdkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtpqxhqcgs.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtmamhmoue.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtvfgwtdnn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtosfaxufw.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtiocyvqtt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtcdksemnf.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtxsocxaad.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdwjpgkz.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtdpfxtjyo.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtirmigfib.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtzxgwpzun.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtgykfrwhs.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtmxknlzyp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtrxhfvagf.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtrcuvhiqs.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmowwpid.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtpfocsboh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtjydxeuvl.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtcgutaizd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtmlnkqxzl.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtcerpufqk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gthktladtd.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtgcsteaad.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gtczqncjbq.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtzavxwmhw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtsvfwwtpn.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtktvzzcru.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtktwvthzy.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtvelahyek.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtpzpdkieq.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtmywrdrxd.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtliajtbtf.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtycrmsobl.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtxuduoffo.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtauafslum.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtyqrqiyte.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtytsdpgvp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtrofcoowx.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtwiyeyvly.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtcqrlxecv.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtaxrwwkwn.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtivilzvcx.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gttkfnyxkn.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtwoqeelog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtdceuxwyv.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtpgpglnjk.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtefgdddih.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtbxqnjwrp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttiaagzo.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtqjypvpqw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsspkqbyv.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtsznttzyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthomasrfb.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtxosjfwnx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gttolhmgnr.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtuoqlpgqf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtbnmpecpz.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtgwzujvek.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtvbsuawss.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtocosjnln.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtxmztipcu.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gttngtytup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtntgligdj.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtgfcoszuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtpnqireqe.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gthlzhtcex.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gtibdqjkwo.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtltsuflss.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtuysitigt.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtsonehrli.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gteeojieyw.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtnppzcupk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtsiseylel.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtbwmlaucu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtcgulllkq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtytxyfdxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtsytdvejk.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtgddnqitb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtrnsptjoq.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtgddzrguz.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtxagajvmy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtdpvzdpuq.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtqbrhlbgd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtznzblhxj.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtcrgubtri.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtigxyiqxb.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtwouhbhem.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtqxnrrotm.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgezwsgpe.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtsxynnuoi.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtvrxfeqmc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtutgorvsy.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtffppbjlx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtuumlkcrq.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtdrqglihk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtfarwbaep.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtwcbvvvsz.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtoghwziwt.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtdbwdoebh.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gttgqgzvwl.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtuwermwfs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtjzexpnan.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gtajqoalpq.html


<!-- 参考信息 -->