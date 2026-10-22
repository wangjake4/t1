代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gt2rlkkzyhr.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylpekizy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycnglwvw.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwroxzzl.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gt2tlsgjehy.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2aflyjcqd.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlyotzkc.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2ewfmimyi.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2ocafdlcf.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2aubosdhm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gt2iqzdlmyn.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gt2dtlvjssx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2onlrbwqf.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2jerkmhcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2xrnwtyhk.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2zlwngvoi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2bmkdmdmb.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2qbegxkjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ssvnavsd.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywkpcnmx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2yqsmdihv.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utxtaqfs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gt2omfgzuow.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohdflsyp.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gt2dhkofrcm.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2eqegnqww.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2ittrvtol.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2awvfvvbw.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yalwqwrc.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwptvbgj.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2srpzfimq.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2ryqerdiv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gt2dtljxgfp.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2xkvtwnij.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2zuzwhhsi.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbkqihvk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gt2puaelhro.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wptqrqok.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gt2qfpjidkq.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gt2lrnpjwue.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijdtfvuo.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2xcwjzpex.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvylzdli.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkblcjne.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2fqczyimm.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2fryvpehr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2qdjzxlfl.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2faiapwwv.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sascbvve.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gt2zdtgieih.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2ynwpkpns.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gt2ypkgmchv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2ltxodevv.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2jykkfzgv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2emmfiwzo.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gt2opwuynvy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2cuduzyfs.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2fzcphvcu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2riuvcelw.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gt2dsjjgnvo.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqftwdkz.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2tokefyph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2nbhnfiqz.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gt2haqvgfkq.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2somdankt.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2qixbtsrx.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gt2vyhkjnvw.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2absrjwkg.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2nwqieedw.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2kfkgkvjr.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2ytsbrxhs.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2yzfiwxmp.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2dudluasu.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2edevvhso.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gt2xgsgzvfw.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gt2lwqkqptl.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gt2wnanxoup.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2nuzysbme.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2ipkxovcs.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2zhqjayfw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2palwiadn.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2aoautetw.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2xygrdimn.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcggexvt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2otcvtmdd.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhghzjrx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2nhlbvvkf.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2eebrcsgb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2dtuoouws.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gt2xitstfwa.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2qscvlmks.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2bqqbucqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2bctjuxwk.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2aryjoxwa.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2lncgxrti.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2rfgeghhm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gt2nfwtmoiv.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2detvcuwh.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2grngzjpu.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqlzrbgv.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2lxaygyca.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rojyiepw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gt2mlczmcgs.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2jehikbff.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2fmmygkbk.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2bfyavtbn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2basnnqhm.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gt2auamlvjm.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gt2vchneurg.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2yenqwedr.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gt2jprciazs.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2ytyrycki.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gt2pscyryox.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2jqtxojrs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gt2klkotfic.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2qmylvvrk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gt2tmcqpepg.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2rbdpxgbc.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gt2mwthmbns.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2bhytrdff.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axdkpwsz.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gt2znyydnkl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2caeyymls.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2tgznnlsa.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gt2lxrhavqc.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2rxxgnagp.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gt2yleosgfx.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2bfewvvnl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjiesumx.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2zfywzoxt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2qhhucpun.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2nbjaihmd.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gt2owmpkxft.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2vtqbctgx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2oqgiqmzd.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2tripgxbq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2ofbdizrx.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2hwwrsmxz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2ovzhsram.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gt2bskxjhqm.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2lwkcjobx.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gt2zyeyfbda.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gt2lpjcbset.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2ngifhvli.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gt2xicmkqmy.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2bstysthr.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2smdlezsp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmbvyjjo.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2bngrugjh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uqolkqzm.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2whfswphw.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2arfcvutc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2anqtdjwy.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2gpskoptl.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2jotmxwfz.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2nioxzbas.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2vizsufov.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2usuxseot.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gt2jeqekvqc.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2opjyoczl.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2dxrzmydc.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2csrewasc.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2rprmclbk.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gt2wookmsom.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2vdgichuv.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gt2eotuqcrl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2ogxjzuai.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2fjhqpiqn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzcnklbw.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gt2uyekexgq.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gt2zwbclxyj.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2gwsxhmca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2dunknmdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gt2eafezhuh.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2nmtduguz.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gt2vshrbgcp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2avdcfjkw.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2abwvncuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gt2hpvqkxph.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2ucspetqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2bzguxtoz.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2mnnubksy.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gt2mbzbthrt.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2mfdhrfkr.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2rlfuzdkz.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2wskmivkr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2rrpnnteo.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gt2jeouxspq.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2dnvjpjqn.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2qaofttto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzifbezx.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2efslmdtt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2jokafdcr.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2pigjtxrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2jiyemxbk.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gt2yxdzabvp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2jaaiiyjn.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhhuiuel.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gt2zznwhigj.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2zkaqedxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gt2jzkkgoqj.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgoadvhg.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gt2bsnqgpty.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gt2xvxffqnv.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gt2lwztekoq.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2oizyktlx.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rukfgdke.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2pmctyodm.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2osoiyznc.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gt2mpwqrcvs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tysyhzny.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2krnopljk.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpvlmkqe.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2bvxcfmwq.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2ewdbzpqs.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2sdyymfyr.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtsqleiv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gt2hvavwqvi.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2kioedvqm.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gt2lqornlfx.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfoqpbbw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbgcwxjt.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gt2dthbvfbu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2gqleutdw.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2pfomhorh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2jifsaxmi.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvtpicuc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2nvujexlw.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2xdgrlzdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2lmghptre.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gt2ievzhspo.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2kjtsbsix.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2maiqmilp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gt2gakxvtzd.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2jvecagyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2hkkrvinh.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2egagsqji.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2yofkhalo.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gt2xosdjwvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gt2krrqhwvv.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2mwfaippt.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2vsfrqymf.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gt2klzssxoh.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2oncumjpz.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gt2yrwegbus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2tfkgycjx.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2llnnvnlj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2qkumasnu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gt2qklastxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2hiegziiv.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2gagozvtg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2plhvnhjn.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2hduscija.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2jagysfgh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2whpvzgtm.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gt2cdpkiufa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2arftrdnk.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqfegooc.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gt2zlbfwfwz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gt2cxhkxknj.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2lpzgztgb.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2luiyzyon.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2gupdnvdr.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gt2zpnknuah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbfcrdbi.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2zsjuwleb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2qppyrdsi.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2rgykcatm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2zyrxgtnt.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2hkgqubgw.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gt2ylypfupk.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gt2aoseusni.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2wgiwiedh.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2ikhrvzcs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gt2nakuoeob.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2ywlrdblv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2bcoigflq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwpwegwv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2xtneotgr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2lwekhqkc.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxwxfwyw.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2lqgfxiad.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2uojvcruz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2plroaaai.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gt2nubkeocy.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2acxzkbxk.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2saeyhjrc.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gt2mtlqrjli.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2ruzcrfjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2uglbyesu.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2nkwcbonh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2rwvbglcg.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfpdbtoy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2msigdbac.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2cqilfahd.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2zxcgzchd.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2fhhhcjbv.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2furfkylw.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2mtlskbee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gt2cgsfpkmf.html


<!-- 参考信息 -->