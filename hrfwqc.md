代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gt2ayjirghh.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2wnjmproe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2jjtmenfa.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2xcxvwbzl.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gt2dfvcsrmi.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2vccqkerw.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gt2vbyxfimu.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlxpaiyp.html

esac
来源：http://dali.tanke756.top/Article/details/gt2jsyeqevf.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gt2uysxnyqp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gt2obemtmjd.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2sbskmkyb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2tseencmd.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gt2aspyfxfc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2hudtevcm.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2lfqdeqdn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gt2bkpahfad.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2clwwndto.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2akdsbuyo.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2knvomcpm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2wmisktci.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2lvcyyzbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2uoiqyeuu.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2xsorevwq.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbmhurox.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2ddwmttrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2tojxyzwv.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2stjfrkgc.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2eapecrkp.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2ydzhfppj.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2dgrhbxqu.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2gndnnxoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gt2rwcwenif.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acinjbnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2czscccqm.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gt2pbcngcvp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2ktcmnegw.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2umebgfeq.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2zkmtixcl.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2stcpbawl.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2zzqqctlz.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2yjamtxio.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gt2bpyogruq.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zejrcccj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnvflbxx.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2daqfhbnk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2kcgjpbgh.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2dukbgile.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hllkdqtg.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2lmazehyv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2iowyrvph.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zfndovyx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2vyevzquh.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2lrlynetf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2kaztzhlz.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gt2zcigsyjl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gt2nllnfmzm.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2utloqqfc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gt2fvavzzzg.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2deokoctz.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2fgltvdxa.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2inqegcht.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gt2uipmtfrt.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2ryomhbib.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqzlahvj.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2mzllpcrj.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gt2slpgausi.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gt2vxjspkdc.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2migqirnh.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2rbanpovu.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2wnxpmnet.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2uiuifjww.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owsqtyrr.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2ssoawuzq.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2wqqbzwix.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2hyelrsad.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwczpnfj.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2svyouqdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2kberhgen.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2lcnrqcvu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2wzbynudh.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gt2ydpijgui.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2vbygbmws.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxpviuqy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zszqbqjl.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2luaeqxua.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ujveitqp.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2cpafrhff.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2tzvuuvsf.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gt2uzmolzve.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gt2dlboiqyz.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gt2gcckapbj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyispups.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2hwsquabx.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gt2gnrbgaht.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gt2hnxtfybd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2oqvnivqh.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gt2aflnljvy.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2ncqrpptd.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2qsdshura.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlncguom.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2tabhfyqb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gt2lemepllv.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oggewhpf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2onpvleoy.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2iitardfo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2ooyerzfi.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2mtsxrryy.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2oifngchv.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2fccdhoyk.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gt2yjtyxvlq.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2jyzpkbjc.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gt2qvfehgxa.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gt2teznuxhk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2soiwrupe.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gt2opulkscq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gt2hhiaauws.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhdcnhvb.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2cuojbvhg.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gt2yledrnvg.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2scynmrvt.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gt2vfhcaynz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2bzghpucs.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2dxfsqamy.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gt2eogmlnjr.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gt2orunlrph.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2gybkkmjs.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anhpflrw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2lncllthg.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gt2ejwzjsge.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2ysaazbvp.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gt2yfhrjgne.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2uwkmbbku.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gt2nrczunec.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2hgwzwcig.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2anculmzz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gt2uhoryhme.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2kiwelxtj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2ndbqhdhk.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gt2vflqjgbj.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gt2ejnlsthm.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gt2poiqfdin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gt2pdqnhwhh.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2earkmutz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2oegpoerv.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gt2khxaqskw.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gt2vgintlgb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fuwybdrg.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2txzcatij.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ddqgkeak.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2xwhetiqm.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2xwbgbenf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gt2yogiugpr.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2nomvrujp.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyhgknad.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2kiiqcyiq.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2qhvvebvs.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gt2mcgjdoao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2hhahwhmg.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2yqmbcufv.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jybvipxx.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2bhzitbyb.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gt2dtuiyfxf.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpdnqkbj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2csblxpuc.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2xemxtkwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2atjrtjta.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gt2fynrkylp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2rszttqmj.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gt2zczqzlba.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gt2gkyfwzup.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2uowiyqol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2qjswtjwr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2tharujdu.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2jbdtzafe.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfmlkfro.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2iqtxprql.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2mtmhjizs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gt2xcqwgxvh.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2ilmqgrrn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gt2jhzuwqdh.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gt2bshgzikv.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gt2giaypjit.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2xcsfgekq.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gt2mcwedvfo.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2jjdotnvo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2aozvvuns.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2mtqrszag.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2uluhwqos.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2nqolikce.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2yyadvwpm.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2vknsjmae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fngkwvuv.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmqvsgka.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2kfkumgiv.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2pdzhwste.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2bxjuyeol.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2rxxsotrj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2kduypluk.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2oejyezqc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gt2znpfmqsy.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2lpfpmvrb.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvqarwvx.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2lbqtenao.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naoneqlk.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2uprjzjut.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2gfaucwlx.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2bswpdvhk.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gt2vsfexnez.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2vroyawal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gt2jnjxyeps.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2ijivxfef.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gt2jwcgkimb.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zinjsnvn.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2tzgwtjhq.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2xprwcomy.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2vivmpkwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mazcghtz.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2fcfcrhcl.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2jmpucfhg.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2isjevqer.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2ojvzhktp.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2xlphxccx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gt2bxsxtplh.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2smmcsidz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2tkomzisp.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gt2nvffvljv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2aforblxz.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gt2inoxxdzt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gt2mugbflpr.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gt2tumbekeh.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2igjotvyk.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2vrxwmoph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2btpwjmkz.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykogznyj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2vlfzkywj.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2zxxlndqk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gt2iymbgvsm.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2vbfonwni.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gt2gifsldvy.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gt2biyrgfmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gt2wiyrwdpi.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gt2nmdopkhz.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2lveaaodk.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2pfvsxsfl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2hmebjplf.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2boqkmtyo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2yusrwnqr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyymobsc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gt2rkdcfykw.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2lkwihllb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2hlkbmunq.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2lybijqck.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2mnfxlqhf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2fryupabm.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2zfkmvykx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2pnxhuqwl.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdkfwlib.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gt2evxevskm.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gt2nyjiyyec.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrlxqtw.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gt2fbslmvpa.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2xeeoabwf.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2vwmpubnt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2dbxztpzt.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2cuhuguop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2zeozowxe.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2cckkkuie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2bjwwyctk.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2foadecjc.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2bnipfvsf.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2zblytecg.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlmmczde.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gt2sbnehtip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2wnaolonp.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2todmdctw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2drqvjslr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yukpjinh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaxwhxom.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2aueixdvq.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2funtkwzi.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2vjwkcdzs.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2fawryeml.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2dwyjlvwz.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2rvdiadaq.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2lsaxnlbz.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2lsvtiazt.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2seuotxoe.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2jwzzkujg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gt2chlaumre.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2mfaqpppk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ioyffzhd.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2gazrnsvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2ayvdkcex.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2jtcifmaq.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2axwgwbkg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gt2wsgfjupc.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gt2uzffhgqe.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2lkftdztp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gt2nzpswkey.html


<!-- 参考信息 -->