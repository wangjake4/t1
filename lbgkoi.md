代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2bqqfhsei.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2vsksvybg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gt2htdkgoky.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mbnshaqw.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gt2opibhted.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vsjmvmbx.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gt2jpuktdcg.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2xtgbkybf.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2pelwjrcr.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gt2ljwmjobr.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2alaopzdd.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2sdhlazve.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gt2lvldrbgb.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2bovwgrwi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2xranyfvb.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2ouzdqgiw.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gt2rclyystj.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2qeweilck.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2bbjrlwjo.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2wjhznocr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2aljavufx.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gt2yzurfhpz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gt2nxkvlbip.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2kkxnulom.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2eupkfwic.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2yyzrjmvj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2muemapwg.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2dbabendl.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbhxfgbw.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2ogfulmfj.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2iqlqigbr.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2znrttnaf.html

esac
来源：http://dali.tianlin.xyz/Article/details/gt2apdmeiye.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gt2alcaampy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2blvigthz.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2ggkovblb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2eyeffsrf.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2vczidheo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2lexdzwpy.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2nwlzmoru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2takurdoc.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gt2hxujaffx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idqakoqa.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gt2ktdyrrsr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gt2faaoomax.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gt2emulwnfz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gt2akscifln.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2rwidwfbf.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmolboym.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gt2kuwedvmu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2yvjwnkeg.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2clodaxqb.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2lzitylcc.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2cveipbpr.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2qrneaoiz.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2xqkmoqua.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gt2ossljfvi.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2gkmpvovi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2wpxvjlyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gt2cdfoqfzn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gt2akmwqper.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2temstvzw.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2ltpalczl.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2gnftaovs.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gt2lxuviigh.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gt2hyswznjm.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2tusxjsji.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpzlrrnt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rznvaqvk.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2kgyojujm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gt2yiqamhgo.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2umpmamqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2pudlfyuh.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2cvvlklbd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2rolqferg.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ethdfuhr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2hoxswjzo.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gt2krgzlryb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2pqtarhez.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gt2ibgxovud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2dscwtuki.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gt2vidakghy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdpnwccb.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gt2kowcvxyw.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2bwmrfzkr.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2qjuhlfvc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gt2trzbwngg.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2daovkqrz.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbkbxvxv.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2ekafgxkx.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2bhlxtors.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2tvjsephg.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2zftucprr.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2tyoitrgq.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlvcnptj.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2bwjvyjfs.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2icnstlyx.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2ypohjqdm.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2iobheacz.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pubefgcx.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2xbjavful.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2fhbgfmwd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gt2winapqry.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2nhdhovhg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2kcxpzndf.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2dbpgkfoq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ekfxppya.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gt2fzcvruwa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arcsvfsx.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baygpldh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2evuqpout.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gt2euvmkknb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gt2qlrwmscg.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azytuzko.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gt2doiobvzm.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2ptclubum.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2wgfvdfmg.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gt2wrdxumav.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2spvxiwhe.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2gudcgwkc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gt2ddplfyzm.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2xjuxixxm.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycbaliay.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2zpnkztmt.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgpjykha.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2ekawgion.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2ymirztad.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2yhmlhyls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gt2jkyoiqid.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvaxhocw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxqmcfub.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvqisujh.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gt2hhfmlsky.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gt2eeveilyr.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gt2xrodcnwu.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2axqacgpi.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sypsuhmo.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2zgxaqegf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2lscrblzq.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gt2vbckmfsq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2wztddrzr.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2xzeixnju.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gt2bhnoduuk.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gt2qlxgqvtb.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2vtfdurrf.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2azoocvjt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2fanlcikd.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gt2lqtrweyl.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gt2erkcpbnq.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2qzneeqjm.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2abwbcczy.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zekdytrf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2szkwsfds.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2fwywmanl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkuodlcu.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2pchjhnxo.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2zrcogsbb.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2mcicuxxo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2tfejjkvg.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gt2dnlotdnf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2vqxclfrw.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gt2zxfuqqgt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2znqzhjki.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2ihxrbagl.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gt2dmuxldkp.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2zoduauhm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gt2qnddsixw.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2vcqyugcr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2ywetazdh.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2owzrixlf.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gt2xjmbetnp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zcjlexes.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2lxrmnxag.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vynqouhd.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2kprjhfla.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gt2bgkucegn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gt2mygbpzfw.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2nhtidzva.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2dllmewkv.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gt2qrowbyid.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gt2hggmxaeh.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2mwozyunk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2ousyfsya.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2ifmnebor.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2gwrerwvy.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2artwiqmi.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gt2zzrhgkrs.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaiokhbu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gt2fvhpgbro.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spsuyamx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gt2lbgnrqfv.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gt2dhjoibex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gt2aylapzbg.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2pmwqzpzr.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2tpfbfdwq.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfmefbfs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gt2eqjkccgd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdjbyzrh.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2ahsunftg.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2sdmovaxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2injamkra.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2lyovirsq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2ybkknksb.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2karrycmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gt2iddmeudy.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwmziule.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gt2rcnsalti.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2exmihjvv.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gt2dlpijxqt.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2mpgelgdg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iabxouxg.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2kgrqcqwb.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gt2hvtpawsb.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gt2pduibxlo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2ojivzgou.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2iobrdrxi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2owziyaxz.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2aykfvnsx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2wsqclwjs.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwlxhgpl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2caxkymgq.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gt2aoclzpty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2wmlnaicg.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2rrrhhfke.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2lfjnziob.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2ucxihred.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gt2xatjmbxj.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2kthqewvm.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2vvqppxvo.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2rihwjohy.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucakdaxh.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2wezbmzdc.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2pxcwuvgd.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2qzegedjd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2kwhsmaoz.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2ebgsglrm.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2pqbplwpw.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gt2lnogcsib.html

#endif
来源：http://dali.316326.xyz/Article/details/gt2hstguqdv.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2jyxghlzg.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gt2pjwvzufy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sojtilrc.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gt2sldwzjbm.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nccionoi.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2caxmigdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipcjqmsn.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gt2qnmarbtp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gt2blasyaco.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2trpymjge.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2ruqhbezm.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gt2gbsakuey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2nfthcnqh.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2tqeitwul.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gt2jecnkghb.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2hunrfwyi.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2uxdjrblq.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gt2owxenbhp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gt2hlaamjmr.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2njhtuxhs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnbehpil.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2yhgffqee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2hyemuarn.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gt2jygduagz.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gt2rhqjdyeh.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2dgokqagd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chkbkqmy.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2yaplzjto.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gt2mdbaucsx.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2uaoxmknu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2ysbwypfo.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2hziasygb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2awvbkzxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2oxuxlepu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxudftna.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xoqfaigx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gt2griheoha.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2orllvvzh.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2owjgplvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2zekjnpnw.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2wmnqkwlr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2xvoogwpb.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwardtuj.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2lotzimnh.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2bidmosgs.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dkcnsqdg.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2tdvnkxxn.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gt2nqamweiw.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaurusli.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtumlly.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2konfsbrq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2irbkmdcd.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2nouqlsnh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eccpmijn.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gt2wxhmhfbk.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2crtidxhx.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2qirwnydk.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gt2aaqfuwgp.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2hhrzpmjp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2rxrclxgs.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2goncfogk.html


<!-- 参考信息 -->